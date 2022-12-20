# Time Converter
## Description
Create a function called timeConverter that receives a positive number of seconds and returns a string based on the number. "Days: 1, Hours: 5, Minutes: 40 and seconds: 5"

4000 --> "days: 0, hours: 1, minutes: 6, and seconds: 4"

40000 --> "days: 0, hours: 11, minutes: 6, and seconds: 4"

150000 --> "days: 1, hours: 17, minutes: 40, and seconds: 0"

## **Solution:** 📋✔️🎊✨

```
Funcion Resultado = tiempo (n)
	Escribir " Ingrese la cantidad en segundos que desea calcular: " Sin Saltar
	Leer s
	n = 100000
	min = trunc(s * (1 / 60)) 
	hora = trunc(min * (1 / 60 )) 
	dia = trunc(min * (1 / 1440 )) 
	anio = trunc(dia * (1 / 365 ))
	Escribir "Años: ", anio, ", Días: ", dia, ", Horas: ", hora, ", Minutos: ", min, ", Segundos: ", s
FinFuncion


Algoritmo Time_Converter
	Escribir tiempo(100000)
FinAlgoritmo
```
![1](https://user-images.githubusercontent.com/107091326/208581923-4db2a68f-7101-4afa-8d3c-ff7340c9b3b9.JPG)


---

# Compare distances
## Description
Create a function called compareDistances that asks for 5 numbers, these can be positive or negative, add the positives with positives and negatives with negatives, the function should return true if there is more distance to 0 with positives or false if the distance is greater with negatives .

4, 12 , 100, 8, -60 --> true

40, 120 , 10, -80, -91 --> false

## **Solution:** 📋✔️🎊✨

```
Funcion Resultado = distancia ()
	Definir NumerosPositivos, NumerosNegativos, suma Como Entero
	Definir Resultado Como Logico
	
	Escribir " Ingrese 5 numeros positivos o negativos"
	i = 0
	suma = 0
	NumerosNegativos = 0
	NumerosPositivos = 0
	
	Para i = 1 Hasta 5 Con Paso 1 Hacer
		Escribir " Ingrese el #", i Sin Saltar
		leer n
		suma = suma + n
		Si n >= 0 Entonces
			NumerosPositivos = NumerosPositivos + n
		SiNo
			NumerosNegativos = NumerosNegativos + n
		Fin Si
	Fin Para
	
	Resultado = NumerosPositivos > abs(NumerosNegativos)
	Escribir " Sumatoria: " suma
	
FinFuncion

Algoritmo Compare_Distances
	Escribir distancia()
FinAlgoritmo
```
![2](https://user-images.githubusercontent.com/107091326/208602425-dea2eda0-215a-4e16-b4ed-e4cefdf69cdd.JPG)

