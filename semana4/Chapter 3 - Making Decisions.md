# Chapter 3 - Making Decisions

## 1.	Respuesta A, B, C, E, F y G.
En el switch se permite el uso de los int, byte, short y char, igualmente se pueden usar los enums y los Strings. Para el caso del var dependerá si el tipo es soportado por el switch, pero se podría usar igual.
## 2.	Respuesta B
La clave para saber que es la B es poner atención en que se entró al primer if de manera correcta y dentro de ese if existe otro if y un else, el if no se cumple por lo cual imprime lo que tenga el else.
## 3.	Respuesta A, D, F, y H.
Todo lo que puede ir en el lado derecho de un for each son cosas que se pueden iterar (D y H) y arreglos (A y F).
## 4.	Respuesta F.
Al switch le hace falta el bloque de default para ejecutarse correctamente. En el caso de tenerlo se imprimiría correctamente “Turtle”.
## 5.	Respuesta E.
Existe 3 bucles for, el primero y el tercero se ejecutan sin problema, pero el segundo, antes de usar el sout tiene la palabra “continue;” y salta al tercer for, es por lo que 1 línea no compila.
## 6.	Respuesta C, D y E.
La C hace referencia a que 1 ciclo for antes de ejecutarse se valida la condición lo cual es correcto, la D menciona algo parecido a una pregunta anterior, un switch debe asegurar que va a retornar 1 resultado (bloque default) y la E dice que el do-while primero hace y luego evalúa (traducción de la palabra) a diferencia del while que primero evalúa y luego ejecuta.
## 7.	Respuesta B y D.
Se debe tener cuidado con las posiciones de los arreglos (empiezan por 0) y sus longitudes (empiezan en 1) por lo que cuando se quiere recorrer un arreglo se use el length -1, la opción B y D es prácticamente lo mismo, pero 1 empieza por el índice 0 y la otra por índice más alto.
## 8.	Respuesta G.
El problema de compilación son los 2 else-if, están declarando la variable bat y luego la intentan volver a usar esa variable haciendo que entre en conflicto, suponiendo que el código compilara entrara en el primer if y mostraría el “int”.
## 9.	Respuesta B, C y E.
La clave es darse cuenta de que BUNNY solamente se ejecutará 2 veces (por su condición) entonces tenemos que romper el ciclo de RABBIT o contar el bucle de BUNNY para el contador solamente se aumente 2 veces.
## 10.	Respuesta E.
El primer error de compilación es el continue dentro del switch, se hace uso del DayOfWeek.MONDAY lo cual no es un int.
## 11.	Respuesta A.
El bloque switch se ejecuta correctamente entrando a MAMMAL retornando un int 3 e imprimiéndolo con el SOUT.
## 12.	Respuesta C.
Primero me doy cuenta de que bulce while se va a ejecutar 2 veces para la primera iteración será 7 + 4 y después 6 + 6 sumando todo me da 23.
## 13.	Respuesta G.
Solamente hace falta unos paréntesis que rodean keepGoing en el while para que funcione correctamente.
## 14.	B, D y F.
El primer for del pingüino es correcto haciendo de tipo int, para el seugndo for-each es parecido, pero con Char y para el ultimo se usa el genérico de <Integer>.
## 15.	Respuesta F.
El código no compila, el segundo case esta intentando anidar instrucciones con “:” y eso no es válido.
## 16.	Repuesta A, B y D.
Se debe imprimir al revés por lo que siempre la primera posición del arreglo debe ser length -1 y debe acabar con la posición [0], es parecido a la pregunta de length de esta misma lección.
## 17.	Respuesta B y E.
Los resultados son 10, 3 y 3 el 10 es del primer while el segundo 3 es del do-while (se ejecuta por lo menos 1 vez) y el otro 3 es del for.
## 18.	Respuesta C y E.
Pattern machine dentro de un if se usa instance of y Flow scoping determina si la variable está disponible dentro del flujo.
## 19.	Respuesta E.
El código no compila porque la serpiente esta declarada en el cuerpo del do-while.
## 20.	Respuesta A y E.
El break en L2 hace que salgamos de 2 loop cada que entremos ya que existe 1 loop infinito y la otra opción termia el primero y el segundo loop por lo que termina el programa.
## 21.	Respuesta E.
4 líneas, el switch no es compatible con el Long, en la line del case 10 hace falta un “;”, para el case 20 tiene un “;” de más y existen 2 case 30.
## 22.	Respuesta E.
Se ejecuta 1 vez el switch entrando en el default -> case 3 y luego 2 veces el while 5 2 1.
## 23.	Respuesta F.
Parece ser que entraría en else pero no tiene ningún if de procedencia por lo cual ninguna condición se cumple.
## 24.	Respuesta G.
No se usa la palabra in se usa “:”.
## 25.	Respuesta D.
La variable dentro del siwtch se incremente 3 veces entrando por el default, como la variable inicio en -1 termina en 2.
## 26.	Respuesta F.
Contiende 1 bucle infinito ya que la variable R se actualiza fuera del do-while.
## 27.	Respuesta F.
El bloque case no esta regresado 1 valor y los switch siempre deben regresar 1 valor.
## 28.	Respuesta F.
Se esta duplicando la variable esto hace que den un error de compilación (línea 41 y 43).
29.	Respuesta C.
Lo importante es seguir el buce y ver que primero incrementa después imprime, inicia en -1 y termina en 6.
