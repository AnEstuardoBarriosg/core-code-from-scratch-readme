# Total price
## Description
Create a function called TotalPrice that takes 2 parameters, price and VAT, and returns the price including VAT. if the price exceeds 3000 a 10 percent discount is made on the total price.

## **Solution:** 📋✔️🎊✨
```
Algoritmo example_TotalPrice
	Escribir " Ingrese el precio del producto sin IVA: " Sin Saltar
	Leer precio
	IVA = 0.12

	IVA2 = precio * IVA
	preciofinal = IVA2 + precio
	
	preciofinal2 = preciofinal * 0.10
	preciofinal3 = preciofinal - preciofinal2
	
	Si precio > 3000 Entonces
		Escribir " El total del producto con IVA es de: Q" preciofinal
		Escribir " El total del producto con IVA y el descuento del 10% es de: Q" redon(preciofinal3)
	SiNo
		Escribir " El total del producto con IVA es de: Q" preciofinal
	FinSi
	
FinAlgoritmo
```
![3](https://user-images.githubusercontent.com/107091326/208017723-5e520324-c5aa-41b7-b134-7fe9c4b37df8.JPG)
![4](https://user-images.githubusercontent.com/107091326/208017778-e32b1dd9-da2c-4f0d-948d-4cbad4664830.JPG)


---

# Total price
## Description
Create a function called TotalPrice that takes 2 parameters, price and VAT, and returns the price including VAT. if the price exceeds 3000 a 10 percent discount is made on the total price.

## **Solution:** 📋✔️🎊✨
```
Algoritmo example_Reverse_Direction_And_Size
	Definir palabra, x Como Caracter
	Definir cantidad Como Entero

	Escribir " Ingrese alguna palabra: " Sin Saltar
	Leer palabra
	
	cantidad = Longitud(palabra)
	x = ""
	
	Mientras cantidad >= 0 Hacer
		x = x + Mayusculas(Subcadena(palabra,cantidad,cantidad))
		cantidad = cantidad -1
	FinMientras

	
	Escribir " La palabra invertida es: ", x
	
FinAlgoritmo
```
![5](https://user-images.githubusercontent.com/107091326/208034763-c6199048-ab65-43cc-9aac-911f5ad4641e.JPG)


