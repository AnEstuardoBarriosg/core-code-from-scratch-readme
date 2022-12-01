# Register form
## Description 
You are given the task to create a registration form for new users, this form should ask the user for the following information:

First name
Last name
Age
Email
Address
At the end of the program, you should print all the information added from the user in a friendly way

## **Solution:** 📋✔️🎊✨

```
Algoritmo RegisterForm
	Definir nombre, apellido, correo, direccion Como Caracter
	Definir edad Como Entero
	Escribir ' ********** FORMULARIO ********** '
	Escribir ' Digite su primer nombre: ' 
	Leer nombre
	Escribir ' Digite su primer apellido: '
	Leer apellido
	Escribir ' Digite su edad: '
	Leer edad
	Escribir ' Digite su correo electronico: '
	Leer correo
	Escribir ' Digite su direccion de domicilio: '
	Leer direccion
	Borrar Pantalla
	Escribir ' *****DATOS DEL USUARIO*****'
	Escribir ' Nombre: ' nombre+' '+apellido
	Escribir ' Edad: ' edad
	Escribir ' Correo Electronico: ' correo
	Escribir ' Direccion de domicilio: ' direccion
	Escribir ' ***************************'
FinAlgoritmo
```
![Captura3](https://user-images.githubusercontent.com/107091326/204947572-08305098-69e2-4663-b9bb-5337d4a0e3b6.JPG)

![Captura4](https://user-images.githubusercontent.com/107091326/204947516-e0615e43-e900-48ad-a08f-ce1f5180a492.JPG)


---

# Mod
## Description - Mod in PSeInt Challenge
The challenge for you now is to create a PSeInt program that will receive a number from the user and add the mod operator using the even/odd case ( X % 2 ) where X is the user input

## **Solution:** 📋✔️🎊✨

```
Algoritmo Mod
	Definir num, resultado Como Real
	Escribir ' Digite un numero entero: '
	Leer num
	resultado = num % 2
	Si resultado == 0 Entonces
		Escribir ' El numero ' num ' es par '
	SiNo
		Escribir ' El numero ' num ' es impar '
	Fin Si
	Escribir ' El residuo es: ' resultado
FinAlgoritmo
```
* Para numeros impares el residuo siempre será 1

![Captura](https://user-images.githubusercontent.com/107091326/204940541-6399ab9e-3065-4bed-a956-3082d60dbe43.JPG)

* Para numeros pares el residuo siempre será 0

![Captura2](https://user-images.githubusercontent.com/107091326/204940685-eeeaa0f4-7003-4f7f-ba27-6c51a29491e5.JPG)

