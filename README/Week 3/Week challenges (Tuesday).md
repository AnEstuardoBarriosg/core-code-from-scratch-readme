# Simple calculator with Switch
## Description
For this challenge you will be performing a simple calculator using Switch (Segun), this calculator can perform the following operations:

1. Sum (+)
2. Subtract (-)
3. Multiplication (*)
4. Division (/)

The calculator must ask the user for two numbers, after asking for the two numbers, you must ask for the operation to be performed, keep in mind that you must show the user the options available (+, -, *, /). The first thing that must be done is to validate that the operation that the user entered is valid, if it is not a valid option, the user must be shown an error message, for example: ⚠️ La operación no es valida and terminate the program. If the operation is valid, show the message: Procesando: <OPERACIÓN A REALIZAR> For, example: if the user has entered the numbers 10 and 15 as well as the operation *, the message should read: Procesando: 10 * 15. After this message the result of the operation must be displayed, following the previous example, the result of operating 10 * 15 is 150, so the program should return: Resultado: 150. Remember to use Switch (Segun) to identify which operations you should execute.

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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
				Esperar Tecla
			"5": 
				Limpiar Pantalla
				Escribir ""
				Escribir " Esta saliendo del programa..."
			De Otro Modo:
				Limpiar Pantalla
				Escribir op, " No es una opcion correcta. Intentelo de nuevo"
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
				Esperar Tecla
		Fin Segun
	Hasta Que op =="5"
FinAlgoritmo
```

![205779266-4aad12dd-1bed-402d-989f-b908717b2f3d](https://user-images.githubusercontent.com/107091326/206066486-94ca42d5-9353-4ebe-bf38-4419af086541.gif)


---

# Simple calculator with Do While
## Description
For this challenge we are going to use the simple calculator that we made in the challenge 02 but now adding the functionality to perform a calculation again without finishing the program. The program should ask us if we want to use another operation and if the user answers yes then we can perform a new operation. To solve this challenge remember to use Do while (Repetir Hasta Que).

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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
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
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
				Esperar Tecla
			"5": 
				Limpiar Pantalla
				Escribir ""
				Escribir " Esta saliendo del programa..."
			De Otro Modo:
				Limpiar Pantalla
				Escribir op, " No es una opcion correcta. Intentelo de nuevo"
				Escribir " Pulsa una tecla para volver al menú principal y realizar otra operación..."
				Esperar Tecla
		Fin Segun
	Hasta Que op =="5"
FinAlgoritmo
```
![205779266-4aad12dd-1bed-402d-989f-b908717b2f3d](https://user-images.githubusercontent.com/107091326/206066468-b3bf9d4a-c165-4082-bfe5-33bf45bf7b4c.gif)

