# Simple calculator
## Description
For this challenge you will be performing a simple calculator, this calculator can perform the following operations:

1. Sum (+)
2. Subtract (-)
3. Multiplication (*)
4. Division (/)

The calculator must ask the user for two numbers, after asking for the two numbers, you must ask for the operation to be performed, keep in mind that you must show the user the options available (+, -, *, /). The first thing that must be done is to validate that the operation that the user entered is valid, if it is not a valid option, the user must be shown an error message, for example: ⚠️ La operación no es valida and terminate the program. If the operation is valid, show the message: Procesando: <OPERACIÓN A REALIZAR> For, example: if the user has entered the numbers 10 and 15 as well as the operation *, the message should read: Procesando: 10 * 15. After this message the result of the operation must be displayed, following the previous example, the result of operating 10 * 15 is 150, so the program should return: Resultado: 150. Remember to use conditionals to identify which operations you should execute.

## **Solution:** 📋✔️🎊✨

```
Algoritmo Simplecalculator
	Definir a, b, suma, resta, multiplicacion, division Como Real
	Definir op Como Caracter
	
	Repetir
		Limpiar Pantalla
		Escribir " ***** MENÚ PRINCIPAL *****"
		Escribir " 1. Suma de dos numeros"
		Escribir " 2. Resta de dos numeros"
		Escribir " 3. Multiplicacion de dos numeros"
		Escribir " 4. Division de dos numeros"
		Escribir " 5. Salir"
		Escribir " Elige la opcion que desee (0 - 4)..." Sin Saltar
		Leer op
		Segun op Hacer
			"1":
				Limpiar Pantalla
				Escribir " *****Suma de dos numeros*****"
				Escribir ' Ingrese su primer numero: '
				Leer a
				Escribir ' Ingrese su segundo numero: '
				Leer b
				suma = a + b
				Escribir " La suma de " a " y " b " es: " suma
				Escribir " Pulsa una tecla para volver al menú principal..."
				Esperar Tecla
			"2":
				Limpiar Pantalla
				Escribir " *****Resta de dos numeros*****"
				Escribir ' Ingrese su primer numero: '
				Leer a
				Escribir ' Ingrese su segundo numero: '
				Leer b
				resta = a - b
				Escribir " La resta de " a " y " b " es: " resta
				Escribir " Pulsa una tecla para volver al menú principal..."
				Esperar Tecla
			"3":
				Limpiar Pantalla
				Escribir " *****Multiplicacion de dos numeros*****"
				Escribir ' Ingrese su primer numero: '
				Leer a
				Escribir ' Ingrese su segundo numero: '
				Leer b
				multiplicacion = a * b
				Escribir " La multiplicación de " a " y " b " es: " multiplicacion
				Escribir " Pulsa una tecla para volver al menú principal..."
				Esperar Tecla
			"4":
				Limpiar Pantalla
				Escribir " *****Division de dos numeros*****"
				Escribir ' Ingrese su primer numero: '
				Leer a
				Escribir ' Ingrese su segundo numero: '
				Leer b
				division = a / b
				Escribir " La division de " a " y " b " es: " division
				Escribir " Pulsa una tecla para volver al menú principal..."
				Esperar Tecla
			"5": 
				Limpiar Pantalla
				Escribir ""
				Escribir " Esta saliendo del programa..."
			De Otro Modo:
				Limpiar Pantalla
				Escribir op, " No es una opcion correcta. Intentelo de nuevo"
				Escribir " Pulsa una tecla para continuar..."
				Esperar Tecla
		Fin Segun
	Hasta Que op =="5"
FinAlgoritmo

```

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/107091326/205779266-4aad12dd-1bed-402d-989f-b908717b2f3d.gif)

---


# Special number
## Description
You must create the code that follows the following logic, if the given number is 100, take this number as special and show the following message: "This is a special number!", but if the number is less than 1000, multiple of 10 and different from 100, you must show the following message: "This number is almost special". if none of the given conditions are met show the following message: "Just a regular number". Another developer was trying to program the logic, but apparently couldn't, you need to fix the code to work properly

This was the code from the developer
```
Algoritmo specialNumber
	Leer n
	Si n == 100 Entonces
		Imprimir 'This is a special number'
	FinSi
	Si n < 1000 Entonces
		Imprimir ''
	SiNo
		Imprimir 'Just a regular number'
	FinSi
	Si n % 10 == 0 Entonces
		Imprimir 'This number is multiple of 10'
	FinSi
FinAlgoritmo
```
## **Solution:** 📋✔️🎊✨
```
Algoritmo SpecialNumber
	Definir n Como Real
	Leer n
	Si n==100 Entonces
		Imprimir  ' Este es un numero especial'
	SiNo
			Si (n < 1000) & ( n % 10 == 0) Entonces
				Escribir ' Este numero es casi especial'
			SiNo
				EScribir ' Este es un numero regular'
			FinSi
	FinSi
FinAlgoritmo
```
![1](https://user-images.githubusercontent.com/107091326/205790985-e82b7d64-a9c9-4a49-aadb-19f7e1901722.JPG)
![2](https://user-images.githubusercontent.com/107091326/205790992-6fe55e7e-e9ef-47c0-917c-3ca8f3a6634d.JPG)

![3](https://user-images.githubusercontent.com/107091326/205790957-9f205cf4-21a1-4b97-bcd6-17abc52dc39e.JPG)



