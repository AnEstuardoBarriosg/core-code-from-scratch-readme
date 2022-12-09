# Multiplication Tables with For
## Description
For this challenge you will create a program to calculate the multiplication tables for a given number using the For(Para) loop. The user must enter a number and then the multiplication table for the number must be printed.

## **Solution:** 📋✔️🎊✨

```
Algoritmo MutiplicationTablesWithFor
	Definir n, i, j, respuesta Como Entero
	
	Escribir " ******* Multiplication Tables *******"
	Escribir " Ingrese hasta que numero desea ver la tabla: " Sin Saltar
	Leer n
	Escribir " Ingrese la tabla a mostrar: " Sin Saltar
	Leer j
	
	Para i=0 Hasta n Con Paso 1 Hacer
		respuesta = j * i
		Escribir j, " X ", i, " = ", respuesta
	Fin Para
	
FinAlgoritmo
```
![1](https://user-images.githubusercontent.com/107091326/206591094-9d3f0904-4577-46b5-8417-5bcd127a19b7.JPG)

---
# Ascending and Descending Numbers
## Description 
For this challenge we are going to print numbers in ascending or descending order. The user must enter a number, then he must enter if he wants to print the numbers in ascending or descending order. If the user chooses ascending, the numbers will be printed from the number 0 to the number entered, otherwise the numbers will be printed descending from the number entered to the number 0.To solve this challenge remember to use the For(Para) loop.

## **Solution:** 📋✔️🎊✨

```
Algoritmo AscendingAndDescendingNumbers
	Definir n, i, Como Entero
	Definir op Como Caracter
	
	Escribir " ***** Ascending and Descending Numbers ***** "
	Escribir " Ingrese un numero entero: " Sin Saltar
	Leer n
	Escribir " Que operación desea ejecutar?: "
	Escribir " 1. Imprimir en orden Ascendente"
	Escribir " 2. Imprimir en orden Descendente"
	Escribir " Ingrese la opción a elegir: " Sin Saltar
	Leer op
	
	Segun op Hacer
		"1":
			Para i=0 Hasta n Con Paso 1 Hacer
			Escribir i
			Fin Para
		"2":
			Para i=n Hasta 0 Con Paso -1 Hacer
			Escribir i
			Fin Para
		De Otro Modo:
			Escribir " La opción es incorrecta"
	Fin Segun
FinAlgoritmo
```
![2](https://user-images.githubusercontent.com/107091326/206593357-6097dd46-c43a-40f7-80ad-33b893703524.JPG)


---
# Greetings
## Description
For this challenge, you need to create a program that prints a greeting based on an hour entered. The program should do the following:

* Print Buenos dias! if the hour is from 0 to 12
* Print Buenas tardes! if the hour is from 13 to 18
* Print Buenas noches! if the hour is from 19 to 23
* Ask the user if he wants to perform another greeting. If the answer is Si, the program must start again.
* At the end of the program, print out the number of times the program has greeted.

## **Solution:** 📋✔️🎊✨

```
Algoritmo Greetings
	Definir h, CantidadSaludos Como Entero
	Definir op Como Caracter
	CantidadSaludos = 0
	op = "Si"
	
	Mientras op== "Si" Hacer
		Escribir " ****** Cheers ******"	
		Escribir " Ingrese la hora actual (0-23)"
		Leer h
		
		Si h <= 12 Entonces
			Escribir " Buenos días!"
		SiNo
			Si h <= 18 Entonces
				Escribir " Buenas tardes!"
			SiNo
				Escribir " Buenas noches!"
			FinSi
		Fin Si
		
		CantidadSaludos = CantidadSaludos + 1
		Escribir " Desea continuar? Si / No "
		Leer op	
		Limpiar Pantalla
	FinMientras	
	
	Escribir " La cantidad de saludos realizada fue de: " CantidadSaludos
FinAlgoritmo
```
![5](https://user-images.githubusercontent.com/107091326/206601339-000c0d21-0ebb-4733-a28d-237c00e28449.JPG)

