# Reto-4 aprendiendo a usar mermaid

Primero, hice el diagrama que sirve para mostar el algoritmo para calcular los números primos anteriores a un natural de la forma pro mediante el uso de mermaid. A pesar de haberlo hecho de la forma pro, no me quedó muy pro pero la intención es lo que cuenta, pienso yo.

![](https://i.ibb.co/DY4c97B/mermaid-diagram-2023-09-10-180617.png),

Segundo, también hice el diagrama de flujo en mermaid del algoritmo que calcula de forma aproximada la raíz cuadrada de un número n, basado en el método de Newthon-Raphson, nuevamente no quedó tan pro pero la intención es lo que cuenta.

![](https://i.ibb.co/6XWxp7G/raices.png)

Ahora, en pseudocódigo así quedaría el algoritmo para determinar los números primos.

```pseudocode
[Variables]
  n : entero
  i : entero
inicio
    lista desde 1 hasta n-1
      i=2
mientras i^2<n hacer
    si i^2>n "todos los números no descartados de la lista son primos anteriores a n"
  descartar múltiplos de i de la lista
      i=entero inmediatamente posterior que no se haya descartado
repetir para el nuevo i

fin mientras
fin
```pseudocode


Ahora, el pseudocódigo para determinar la raíz aproximada de un número natural n.

```pseudocode
```pseudocode
