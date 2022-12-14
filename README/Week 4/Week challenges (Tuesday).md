# Predefined functions
## Description
The predefined functions of pseint, are codes already integrated in the program to be used when the user requires it, normally they are mathematical functions or functions for text strings.

```
- Predefined functions
    - Maths
        - abs
        - trunc
        - redon
        - azar
    - Chain
        - longitud
        - mayusculas
        - minusculas
        - subcadena
```
## **Solution:** 📋✔️🎊✨

### abs
Returns the absolute value of the number.

```
Algoritmo PredefinedFunctions
	Escribir " Digite un numero entero: " Sin Saltar
	Leer n
	
	r = abs(n)
	Escribir " El valor absoluto de " n " es: " r
FinAlgoritmo
```
![1](https://user-images.githubusercontent.com/107091326/207477287-1086c3a7-e97b-4dac-90a1-18e5d9d96072.JPG)

## trunc
Returns the integer part of the number.

```
Algoritmo Trunc_Example
	Escribir " Digite un numero entero: " Sin Saltar
	Leer n
	
	r = trunc(n)
	Escribir " La parte entera de " n " es: " r
FinAlgoritmo
```
![2](https://user-images.githubusercontent.com/107091326/207477845-07337b10-f3e7-46a4-bb5c-422f92922241.JPG)

## redon
Returns the nearest integer.


```
Algoritmo Redon_Example
	Escribir " Digite un numero entero: " Sin Saltar
	Leer n
	
	r = redon(n)
	Escribir " La parte entera de " n " es: " r
FinAlgoritmo
```
![3](https://user-images.githubusercontent.com/107091326/207477998-34dc0d56-255e-41ac-91f3-b5c880a1cefe.JPG)

## azar
The azar(x) function returns a random integer from 0 to x-1. The function aleatorio(x,y) returns a random integer between x and y.


```
Algoritmo Azar_Example
	Escribir " Cual numero será el limite: " Sin Saltar
	Leer n
	
	r = azar(n)
	Escribir " El numero aleatorio entre 0 y " n " es: " r
FinAlgoritmo
```
![4](https://user-images.githubusercontent.com/107091326/207482010-44a5e4fb-5c90-4c09-8502-0139d98b35b8.JPG)

## longitud
The longitud function returns the number of characters the string contains. If it does not contain any characters, it is considered a null or empty string and its length is zero.

```
Algoritmo Longitud_Example
	Escribir " Digite algo: " Sin Saltar
	Leer n
	
	r = Longitud(n)
	Escribir " La longitud de la cadena de texto digitada es de " r
FinAlgoritmo
```
![5](https://user-images.githubusercontent.com/107091326/207482462-9e88b242-25f2-4b9a-bfd0-3e98c2c48ff2.JPG)

## mayusculas
Returns the passed string in uppercase.

```
Algoritmo Mayusculas_Example
	Escribir " Digite algo en minusculas: " Sin Saltar
	Leer n
	
	r = Mayusculas(n)
	Escribir " Usted digito: " n
	Escribir " Aplicando la funcion Masyuculas  la oración quedaría de la siguiente forma: " r 
FinAlgoritmo
```
![6](https://user-images.githubusercontent.com/107091326/207482904-321fa5c4-39b7-48e7-bf13-6f80ec9e9546.JPG)

## minusculas
Returns the passed string in lowercase.

```
Algoritmo Minusculas_Example
	Escribir " Digite algo en Mayusculas: " Sin Saltar
	Leer n
	
	r = Minusculas(n)
	Escribir " Usted digito: " n
	Escribir " Aplicando la funcion Minusculas  la oración quedaría de la siguiente forma: " r 
FinAlgoritmo
```
![7](https://user-images.githubusercontent.com/107091326/207483029-53863779-93dd-4668-82ea-f94842233569.JPG)

## subcadena
Returns a substring of text: Subcadena(string, from, to)

```
Algoritmo Subcadena_Example
	Escribir " Digite algo: " Sin Saltar
	Leer n
	
	r = Subcadena(n,5,10)
	Escribir " Usted digito: " n
	Escribir " Aplicando la funcion Subcadena la oración quedaría de la siguiente forma: " r 
FinAlgoritmo
```
![8](https://user-images.githubusercontent.com/107091326/207483806-f430f8a0-9e52-4d94-9a28-43eb3a1c3bc7.JPG)


---

# Full name
## Description
Make a program that takes a first name and a last name, then returns a string with both values ​​with the first letter uppercase and the rest lowercase.

## **Solution:** 📋✔️🎊✨
```
Algoritmo FullName
	Escribir " Ingrese su nombre: " Sin Saltar
	Leer nombre
	Escribir " Ingrese su apellido: " Sin Saltar
	Leer apellido
	
	nombre1 = Mayusculas(SubCadena(nombre,0,0))
	nombre2 = Minusculas(Subcadena(nombre,1,9))
	apellido1 = Mayusculas(Subcadena(apellido,0,0))
	apellido2 = Minusculas(Subcadena(apellido,1,9))
	
	Escribir Concatenar(nombre1,nombre2) " " Concatenar(apellido1,apellido2)
FinAlgoritmo
```
![9](https://user-images.githubusercontent.com/107091326/207485024-baaa3d7d-15ae-4ac2-a012-358c2bdc33c5.JPG)

---

# Throw dice
## Description
make a program that simulates the roll of 2 dice 10 times, and display for each roll the values ​​of the two dice separated by a space, in case the 2 dice throw the same value in addition to the result, add a string to the ending that says "the dice are the same".

```
Algoritmo Throw_dice
	Definir d, d1 Como Entero
	
	Escribir " Cuantos tiradas de dados desea tirar?: " Sin Saltar
	Leer n
	
	Para i = 1 Hasta n Con Paso 1 Hacer
		d = Aleatorio(1,6)
		d1 = Aleatorio(1,6)
		
		Si d = d1 & d1 = d Entonces
			Escribir d, " ", d1, " Los dados son el mismo" 
		SiNo
			Escribir d, " ", d1 
		Fin Si
	Fin Para
	
FinAlgoritmo
```
![10](https://user-images.githubusercontent.com/107091326/207486722-63a95e65-1ae9-4ec3-ba82-acbe70d63f80.JPG)

