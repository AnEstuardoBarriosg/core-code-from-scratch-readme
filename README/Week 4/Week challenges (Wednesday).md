# Distance to zero
## Description
Make a program that asks for 5 values ​​and also allows us to know which one is furthest from zero, once obtained it returns that number (the numbers can be negative), showing only the integer part of the number.


## **Solution:** 📋✔️🎊✨
```
Algoritmo Distance_To_Zero
	Escribir " Ingrese la cantidad de numeros a evaluar: " Sin Saltar
	Leer n1
	
	Para i = 1 Hasta n1 Con Paso 1 Hacer
		Escribir " Escriba un numero cualquiera #", i Sin Saltar
		Leer n2 
		
		Si n2 > n1 Entonces
			n1 = n2
		Fin Si
		
	Fin Para
	
	Escribir " "
	Escribir " El valor mas alejado de cero es: " trunc(n1)
FinAlgoritmo
```

![1](https://user-images.githubusercontent.com/107091326/208000292-2140ad1a-7461-4750-ac09-b70fa2c6f6aa.JPG)

---

# Toss coin
## Description
From the data we receive first a name and a value, then another name and another value, using the built-in function aleatorio() we simulate the flip of a coin, We must return the name of the winner in capital letters and the value I win, to avoid cheating, if a player puts a value of zero or negative, the opponent automatically wins, in case both cheat, "game canceled" is returned.

## **Solution:** 📋✔️🎊✨
```
Algoritmo Toss_coin
	
	Escribir " Ingrese el nombre del primer jugador: " Sin Saltar
	Leer nombre1
	Escribir " Ingrese el monto a jugar: " Sin Saltar
	Leer monto1
	Escribir " Ingrese el nombre del segundo jugador: " Sin Saltar
	Leer nombre2
	Escribir " Ingrese el monto a jugar: " Sin Saltar
	Leer monto2
	
	Si monto1 < 0 & monto2 < 2 Entonces
		Escribir " JUEGO CANCELADO! " 
	FinSi
	
	Si monto1 < 0 Entonces
		Escribir " El ganador es: " Mayusculas(nombre2) " monto ganado: 0"
		Si monto2 < 0 Entonces
			Escribir " El ganador es: " Mayusculas(nombre1) " monto ganado: 0"
		FinSi
	FinSi
	
	
	Si Aleatorio(1,2) = 1 Entonces
		Escribir " El ganador es: " Mayusculas(nombre1) " monto ganado: " monto2
	SiNo
		Escribir " El ganador es: " Mayusculas(nombre2) " monto ganado: " monto1
	FinSi
FinAlgoritmo
```
![2](https://user-images.githubusercontent.com/107091326/208003382-2df65f81-d322-461d-84ae-6de416b259a6.JPG)


