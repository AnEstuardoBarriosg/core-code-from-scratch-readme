# Average sales and commission
## Description 
Make a program that asks how many sales the seller had, Once the number of sales is entered, ask for the value of each sale until all are entered, then return as a result the average value of sales, and the commission that the seller will take, If the seller had more than 5 sales, his commission will be 15% of the total value of the sales, if he sold 5 or less, his commission will be only 10%.

## **Solution:** 📋✔️🎊✨

```
Algoritmo AverageSalesAndCommission
	Definir n, sale, commission, j, i, h Como Real
	j = 0
	
	Escribir " Escriba el número total de ventas a ingresar: " Sin Saltar
	Leer n
	
	Para i=1 Hasta n Con Paso 1 Hacer
		Escribir " Escriba el valor de la venta #" i " " Sin Saltar
		Leer sale
		j = j + sale
	Fin Para
	
	h = j / n
	Escribir " "
	Escribir " El valor promedio de las ventas es de: " h
	
	Si n <= 5 Entonces
		commission = j * 0.10
		Escribir " La comision correspondiente para el vendedor es de: " commission
	SiNo
		commission = j * 0.15
		Escribir " La comision correspondiente para el vendedor es de: " commission
	Fin Si
FinAlgoritmo
```

![1](https://user-images.githubusercontent.com/107091326/207222021-392160c9-c66f-47b0-817a-724af0b5fdad.JPG)

---

# Even or odd
## Description
Request a number from 1 to 50, if the number is not between those values, report the error and request it again until you get a valid number, then it shows on the screen all the numbers from 1 to that number, if the number is even it only shows the even numbers, if it is odd it only shows the odd ones.

## **Solution:** 📋✔️🎊✨
```
Algoritmo EvenOrOdd
	Definir n  Como Entero

	Repetir 
		Escribir " Escriba un número entre 1 y 50: " Sin Saltar
		Leer n
		
		Si n < 1 | n > 50 Entonces
			Escribir " Numero invalido!!"
		FinSi
		
	Mientras Que n < 1 | n > 50
	
	par = n % 2 = 0
	impar = n % 2 = 1
	
	Para i = 1 Hasta n Con Paso 1 Hacer
		Si i % 2 = 0 & (par) Entonces
			Escribir i 
		Fin Si
		
		Si i % 2 = 1 & (impar) Entonces
			Escribir i 
		Fin Si

	Fin Para
FinAlgoritmo
```
![2](https://user-images.githubusercontent.com/107091326/207228356-40e3bf38-6373-41c8-8dd6-d9d010932d8f.JPG)
![3](https://user-images.githubusercontent.com/107091326/207228361-43052065-1b29-4cfe-a22f-42c175c7ed41.JPG)


