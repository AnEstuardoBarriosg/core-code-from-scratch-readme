# Cashier
## Description
create a function called "cashier" that pretends to be a panel of a bank should display the text: "select an option: a. to deposit. b. withdraw. c. go out." and have a value called balance that will return when finished and will print it on the screen, its initial value will be 1000. You must repeat the menu until you select the option 'c'

if we select 'a' it invokes another function called 'deposit' that will display a text on the screen that will say 'how much do you want to deposit:' it will add that value to the balance and end the function.

if we select 'b' it invokes another function called 'withdraw' that will display a text on the screen that will say 'how much do you want to withdraw:' it will subtract that value from the balance and end the function.

"select an option: a. to deposit. b. withdraw. c. go out."

a -->

"how much do you want to deposit:"

500 -->

"select an option: a. to deposit. b. withdraw. c. go out."

b -->

"how much do you want to withdraw:"

1400 -->

"select an option: a. to deposit. b. withdraw. c. go out."

c -->

100

## **Solution:** 📋✔️🎊✨

```
Funcion Dinero = depositar()
	Escribir " Cuanto desea depositar?: Q" Sin Saltar
	Leer Dinero
FinFuncion

Funcion Retiro = retirar()
	Escribir " Cuanto desea retirar?: Q" Sin Saltar
	Leer Retiro
FinFuncion

Funcion saldo = cashier() 
	Definir op Como Caracter
	saldo = 1000
	
	Repetir
		Limpiar Pantalla
		Escribir " ***** MENÚ PRINCIPAL *****"
		Escribir " A. Depositar"
		Escribir " B. Retirar"
		Escribir " C. Salir"
		Escribir " Ingrese la opción que desea ejecutar (A-B-C): " Sin Saltar
		Leer op
		
		Segun op Hacer
			"A" :
				Limpiar Pantalla
				Escribir " ***** Depositar *****"
				saldo = saldo + depositar()
				Escribir " Pulsa una tecla para volver al menú principal..."
				Esperar Tecla
			"B":
				Limpiar Pantalla
				Escribir " ***** Retirar *****"
				saldo = saldo - retirar()
				Escribir " Pulsa una tecla para volver al menú principal..."
				Esperar Tecla
			"C":
				Limpiar Pantalla
				Escribir ""
				Escribir " Esta saliendo del programa..."
				Escribir " Su saldo final es de: Q" Sin Saltar
		FinSegun
		
	Hasta Que op == "C"
	
FinFuncion

Algoritmo Cashier_Example
	Escribir cashier()
FinAlgoritmo
```
![1](https://user-images.githubusercontent.com/107091326/209064264-830fbf1a-6c47-4436-a169-3b2496cf0c89.JPG)
![2](https://user-images.githubusercontent.com/107091326/209064267-dff9f0ca-fa62-4acf-abe9-33a8fddb9567.JPG)
![3](https://user-images.githubusercontent.com/107091326/209064271-3f69c306-4040-4d4a-af7c-63e87f111e47.JPG)
![4](https://user-images.githubusercontent.com/107091326/209064277-94ad5233-8988-4318-9b91-37f40569bc4f.JPG)



---

# Weather average
## Description
write an algorithm that loops indefinitely until 'x' is entered which will calculate an average of the weather, note that for each value entered it should ask if it is fahrenheit or celsius, then ask for the value. add everything up and divide by the number of values ​​entered. The result must be returned in celsius, have a function that, in case fahrenheit is entered, transforms it to celsius in order to add them.

## **Solution:** 📋✔️🎊✨

```

```


