# Multiplication Tables
## Description
For this challenge you will create a program to calculate the multiplication tables for a given number using While (Mientras). The user must enter a number and then the multiplication table for the number must be printed.

## **Solution:** 📋✔️🎊✨
```
Algoritmo MultiplicationTables
	Definir n, i, j, respuesta Como Entero
	i = 1
	Escribir " ***** Multiplication Tables *****"
	Escribir " Ingrese la tabla a calcular: " Sin Saltar
	Leer n
	Escribir " *** Tabla del ", n " ***" 
	
	Mientras i <= 10 Hacer
		respuesta = n * i
		Escribir n " * ", i " = ", respuesta
		i = i + 1
	Fin Mientras
```
![6](https://user-images.githubusercontent.com/107091326/206610941-dc6ea524-1a68-4f93-8c95-0b86bb84fb35.JPG)


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
![205779266-4aad12dd-1bed-402d-989f-b908717b2f3d](https://user-images.githubusercontent.com/107091326/206606532-e53fd69e-34e0-4885-a130-00bb7bd1ddd7.gif)
