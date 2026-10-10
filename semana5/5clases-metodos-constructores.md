# 5. Clases, métodos y constructores

## 1.	Respuesta B.
Los varargs se declaran con … después del tipo.
## 2.	Respuesta D.
La palabra this se usa para invocar otro constructor de la misma clase y debe ser la primera línea.
## 3.	Respuesta G.
El constructor por default es el que genera el compilador cuando la clase no tiene ninguno declarado.
## 4.	Respuesta C.
Java no asigna valores por defecto si no manda el parámetro.
## 5.	Respuesta D.
Los objetos inmutables no pueden cambiar después de ser creado de ahí la palabra inmutables.
## 6.	Respuesta A.
String se sobre escribe de default a hello y luego se manda a imprimir.
## 7.	Respuesta B.
Lo que entre en el método m es una copia del valor de i, pero i siempre vale 12.
## 8.	Respuesta C.
Parecido a la pregunta anterior se pasa una copia de a pero a siempre vale 20.
## 9.	Respuesta D.
El display de integer y de string dan la respuesta, integer imprime 5 y string hello.
## 10.	Respuesta E.
Se tiene una variable local lo cual para asignara primero entramos a la clase y luego a la variable price.price = 4;
## 11.	Respuesta B.
Al asignar Jian = bob hacemos que ambas variables estén apuntando al mismo objeto y al modificar jian igual modificamos bob.
## 12.	Respuesta B.
El parámetro varargs siempre tiene que ser el ultimo de la lista y al estar en primer lugar no compila.
## 13.	Respuesta B.
String es inmutable y ala entrar al método se modifica la variable local del método por lo que cuando mandamos a imprimir muestra la cadena cuando fue declarada.
## 14.	Respuesta A y D.
Constructor por defecto invoca el constructor sin argumentos de la super clase y solamente se crea cuando la clase no tiene ningún constructor definido.
## 15.	Respuesta C y F.
Los de simple vista que la clase 2 tiene v2 y class1, y class 3 tiene clase2 la cual tiene class1 por eso se die que class3 has-a v1
## 16.	Respuesta E.
Se imprime el primer z = 6, luego se imprime el z local del método doStuff (5) regresa a imprimir el z del main (6) y termina con el z asignado al inicio que doStuff->doStuff2 asigna como 4.
## 17.	Respuesta A.
Es prácticamente la pregunta anterior cambiando 1 palabra dento del método doStuff haciendo que no compile, doStuff no conoce myScope.z esta fuera de su scope.
## 18.	Respuesta A
Al tener this(“default”) manda a llamar al constructor con parámetro luego si se imprime el no-arguments
## 19.	 Respuesta C.
Parecido al pasado con la palabra this(10) y la clave es el 3 sout que es el de No-argument calculate.
## 20.	Respuesta C.
Nuevamente el constructor con this(String, int) y es seguir los souts.
## 21.	Respuesta A.
Los constructores se mandan a llamar entre ellos por eso no compila.
## 22.	Respuesta A.
Iugal al anterior, los constructores se mandan a llamar entre ellos (no compila por recursividad).
## 23.	Respuesta F.
Parece que entrara al float por como se declaró, pero el método busca el primer método sin boxing ni varargs (double).
## 24.	Respuesta B.
String. A no es válido, tendría que ser … (3 puntos) y string…[] a, es error de sintaxis, por eso solo 3 son correctos.
