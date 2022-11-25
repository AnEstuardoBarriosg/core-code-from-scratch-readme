# Week challenges (Thursday) 📋✔️🎊✨
## Design an algorithm to check if a number is even or odd. If it is even, write that it is even, otherwise write that it is odd. Represent the algorithm in a flowchart.

1. Digite un numero entero
2. Guarde el numero en una varibale "n"
3. Realizar la operacion (n % 2)
5. Si el residuo es cero, entonces el numero es par
6. Mandar a imprimir: El numero es par
7. Si el residuo es diferente a cero, entonces el numero es impar
8. Mandar a imprimir: El numero es impar
9. FIN

---------------------------------------------------------------------------------------------------------------

## Write pseudocode for an algorithm that calculates the age of a person based on date of birth 📋✔️🎊✨
1. Digite el año de nacimiento
2. Guardar el año de nacimiento en una variable "año_nacimiento"
3. Digite el año actual
4. Guardar el año actual en una variable "año_actual"
5. Realizar la siguiente operación (año_actual - año_nacimiento)
6. Imprimir el resultado
7. FIN

---------------------------------------------------------------------------------------------------------------

## Solve this problem: 📋✔️🎊✨
**We are in a room with three chests. We know that at least one has a treasure in it. Each chest has a message, but all the messages are lies.
* Left chest: The middle chest has a treasure
* Middle chest: All these chests have treasures in them
* Right chest: Only one of these chests has treasures.**

![Image](https://user-images.githubusercontent.com/29307118/202836372-19159ef8-14d5-4ecf-b08c-819b05e79f81.png)

**SOLUTION**
Partimos de que todos los mensajes son mentiras:
* El tesoro de la izquierda nos indica que el tesoro de en medio "tiene el tesoro", pero, sabiendo que todo es mentira, se descarta el tesoro de la izquierda.
* El tesoro de en medio nos indica que todos los tesoros poseen "un tesoro dentro", pero, sabiendo que todo es mentira, se descarta el tesoro de en medio.
* El tesoro de la derecha nos indica que solo un tesoro posee realmente el tesoro, pero,  sabiendo que todo es mentira, se descarta el tesoro de la derecha

Realmente los unicos tesoros de los que podemos confiar, son los tesoros de los extremos, ya que no especifican si tienen o no tienen el tesoro dentro de ellos a diferencia de lo que indica el tesoro de en medio. Por lo que es una posibilidad del 50/50, o el tesoro está en el lado izquierdo o derecho... o puede estar en ambos tesoros.
