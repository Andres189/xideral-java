# Chapter 4 – Core APIs

## 1.	Respuesta F.
El código parece ser simple y fácil pero la trampa esta en el String another fish, este es de tipo entero y se le esta asignando la suma de 2 enteros. Eso hace que el código no compile.
## 2.	Respuesta C, E y F.
Para el caso de la opción C se estan poniendo las llaves junto al nombre de la variable, la opción E y F no se esta especificando el tamaño del arreglo a diferencia de sus otras opciones que si lo especifican.

## 3.	Respuesta A, C y D.
Primero la opción B da un error porque no importa que mes o año esta mandando el día 40, otro error es la E que intenta mandar el día 29 de febrero, ese año febrero solo tiene 28 días, la opción F es un error con los nombres MonthEnum.
## 4.	Respuesta A, C y D.
Para saber cuál ifs entran y cuales no es importante saber cuándo estan el el pool de strings y cuando no y saber lo que hace el método intern().
## 5.	Respuesta B.
Se tiene que poner atención en los index de la palabra “aaa” y que el método .insert va a ir recorriendo esta palabra (poner atención donde se estan insertando para recorrer la palabra).
## 6.	Respuesta C.
Es un error de asignación de tipos round espera un Long y se le asingo int, para random se le asigna int y espera un double.
## 7.	Respuesta A y E.
Se tiene que saber cuántas horas por detrás estan, la primera dice que está 4 hora por detrás y el segundo 6, con eso en cuenta se puede deducir fácilmente que la primera es 6 horas mas temprano que la segunda (9:00 y 15:00).
## 8.	Respuesta A, B y F.
La opción A es fácil porque usa charAt y solamente tenemos que contar iniciando por 0 para saber que el 5 es la posición 4, B hace un replace dejando la cadena como “1265” e imprime la posición 3 que es el 5 y la opción F remplaza 123 por 1 dejando la cadena como 145.
## 9.	Respuesta A, C y F.
Primero los arreglos su índice como se vio en otras preguntas el primero siempre es 0 y son de un tamaño definido. La otro es que, aunque sean con valores primitivos usar equals regresa un false.
## 10.	Respuesta A.
Todas son correctas, a diferencia de la pregunta anterior parecida a esta, todas las variables son asignadas correctamente a el tipo de retorno del método.
## 11.	Respuesta E.
Se esta intenta sumar horas a una variable que solo cuenta con año/mes/día.
## 12.	Respuesta A, D Y E.
Lo primero a notar que siempre se añade 1 espacio en blanco a la cadena y la siguiente línea lo elimina (se cancelan), para esta opción se usa el mismo método con 2 parámetros que te dice donde iniciar y donde acabar (1 antes), la versión de 1 parámetro nos dice desde donde iniciar.
## 13. Respuesta B.
Como ya vimos en sesiones pasadas el string es inmutable y el SB es mutable es por eso que usa concat en el String no va a imprimir los !!! mientras que para el SB si lo va a hacer.
## 14. Respuesta A y F.
Para la opción A instancia correctamente el objeto Instant y la opción F es una conversión permitida.
## 15. Respuesta C y E.
el arreglo está definido de manera correcta y el arrays sort lo hace por ASCII primero números, mayúsculas y después minúsculas, para que binarySearch tenga efecto tiene que ser llamado después de un arrays.srot, lo cual se cumple e indica donde insertaría el elemento Pippa.
## 16. Respuesta A, B y G.
La cadena inicial tiene una longitud de 11 caracteres (el \n cuanta como 1 y \ \t cuenta como 2), luego se agregan 2 espacios al inicio de cada palabra (+4) y al final se agrega un \n (+1) = 16. Por ultimo el translateEscapes() hace en cuando usamos \ \t en lugar de tomar 2 caracteres se tome 1 por eso 11-1 = 10.  
## 17. Respuesta A y G.
La A dice que tomara el índice 1 y acabara antes del 2 (1 solo carácter) los que tienen números iguales (2,2) no va a imprimir nada porque donde inicia acaba y le excepción del 6,5 inicia después de donde acaba.
## 18. Respuesta C y F.
Es 7 porque como mencione en preguntas anteriores los STRINGS son inmutables, por lo tanto, varias líneas se ignoran dejando purrtwo, su longitud es de 7, luego la palabra 2c si termina siendo 2cfalse la cosa es como se unas en los ifs, para comprar la cadena se tiene que usar .equals, por eso sale "equals".
## 19. Respuesta A, B y D.
El compare va a regresar un numero positivo porque el arreglo es mayor al segundo para el caso de mismatch arroga un -1 si los arreglos son exactamente igual con eso ya podemos sacar cuales serán positivos o no.
## 20. Respuesta A y D.
## 21. Respuesta A y C.
El método reverse es la manera más fácil de revertir una cadena, muy usando en preguntas de este estilo, y la opción C da mucha vuelta, pero igual llega a los esperando, borrando "Jav" de la cadena inicial, luego agrega "vaJ$" y borra el ultimo carácter con el -1, juntando todo “avaJ".
## 22. Respuesta A.
Las fechas como los strings son inmutables y se imprime tal cual se definió.
