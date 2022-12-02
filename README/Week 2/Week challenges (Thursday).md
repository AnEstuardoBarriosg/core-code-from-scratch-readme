# Truth tables
## Description
You are going to learn about three main logical operations used in programming, these operations are called AND, OR, and NOT. Each of the operations uses booleans as operands, and when applying the operations a result is generated, which is also a boolean, this is easier to check using the Truth Tables for each of the operations, now your task is for you to learn, and add the Truth Tables for each of the operations add them to your README and check if the following operations are correct by answering ✅ or ❌ at the end of each operation

Operations:

Remember that AND can be represented by &

Remember that OR can be represented by |

Remember that NOT can be represented by ~

## **Solution:** 📋✔️🎊✨

1. T & T = T ✅
2. T & F = F ✅
3. F & T = T ❌
4. F & F = F ❌
5. T | T = T ✅
6. T | F = F ❌
7. F | T = T ✅
8. F | F = F ✅
9. ~T = T ❌
10. ~F = T ✅
11. (T & F) | (~F) = T ✅
12. (T | F ) & (F | F) = T ❌
13. ~((T | F ) & (F | F)) & F = T ❌
14. ~((T | F ) & (F | F)) & T = F ❌

---

# Boolean results
## Description
You have been assigned to verify and explain a code created by one of your colleagues, the idea is that you can describe the value that each variable has within the code as well as what was done for each line. What is expected of you is that you add comments below each line showing the value that the variable would have and a short explanation of how that value is reached.

```
Algoritmo boolean
	a <- 5 == 3
	b <- 4 <> 3
	c <- 7 > 7
	d <- 4 < 4
	e <- 100 <= 90
	f <- 40 >= 40
FinAlgoritmo
```

## **Solution:** 📋✔️🎊✨

```
Algoritmo boolean
	a <- 5 == 3 // FALSO; 5 no es igual a 3
	b <- 4 <> 3 // VERDADERO; 4 es diferente de 3
	c <- 7 > 7 // FALSO; 7 no es mayor a 7
	d <- 4 < 4 // FALSO; 4 no es menor a 7
	e <- 100 <= 90 // FALSO; 100 no es menor o igual a 90
	f <- 40 >= 40 // VERDADERO; 40 no es mayor a 40, pero si 40 si es igual a 40
FinAlgoritmo
```

---

# Identify odd and even numbers
## Description
Remember the last challenge about the Mod operator? well, today your task will be to create a program that will be able to detect based on the user input if the number is odd or even. The process should be the following:

The user enters a number
Your algorithm detects if the number is odd or even (remember to use conditional statements Si...Entonces)
Print ‘Número: x es par’ if the number is even (x is the number the user enters)
Print ‘Número: x es impar’ if the number is odd (x is the number the user enters)

## **Solution:** 📋✔️🎊✨

```
Algoritmo IdentifyOddAndEvenNumbers
	Definir num, resultado Como Real
	Definir op Como Caracter
	Repetir
		Escribir ' Digite un numero: '
		Leer num
		resultado = num % 2
		Si resultado == 0 Entonces
			Escribir ' El numero ' num ' es par'
		SiNo
			Escribir ' El numero ' num ' es impar'
		Fin Si
		Escribir ' ¿Desea realizar otra comprobación? Ingrese S para sí.'
		Leer op
		Limpiar Pantalla
	Mientras Que op='s' |  op='S'
FinAlgoritmo
```
* Para numeros pares el residuo siempre será 0

![3](https://user-images.githubusercontent.com/107091326/205193907-93018dcd-e15c-4794-9eb8-cdf9aabdbd8e.JPG)

* Para numeros impares el residuo siempre será 1

![4](https://user-images.githubusercontent.com/107091326/205193942-7c862ebd-b67c-4686-8cb1-e94086fcf19d.JPG)


