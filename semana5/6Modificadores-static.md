# 6. Modificadores, static e inicialización

## 1.	Respuesta B.
Se importa implícitamente java.lang.
## 2.	Respuesta B.
Como mencione antes, java.lang se importa implícitamente.
## 3.	Respuesta B.
Como es un método static se invoca usando el nombre de la clase.
## 4.	Respuesta B.
Los bloques static solamente se ejecutan 1 vez cuando la clase se inicializa.
## 5.	Respuesta A.
Los atributos protectes solamente pueden ser alcanzados por la propia clase, clases del mismo paquete y subclases que estén en otro paquete (herencia).
## 6.	Respuesta C y E.
Static y Public son los únicos válidos para las clases.
## 7.	Respuesta B, C, F y H.
Clases a nivel superior admiten public, abstract, final y srictfp
## 8.	Respuesta C.
El método era privado y no era visible desde Y, cambiarlo a protected lo hace visible.
## 9.	Respuesta A.
Main está dentro de extendedA, puede usar su constructor, aunque sea privado.
## 10.	Respuesta B.
Primero se ejecuta el sout static, luego el que esta dentro de los bloques y por puro descarte solamente queda la opción B.
## 11.	Respuesta C.
Se ejecuta el sout dentro del static, luego main llama al staticMethod y con new se ejecuta el bloque de código.
## 12.	Respuesta D.
Se tiene que poner atención en que primero se manda a llamar el constructor con parámetro, pero luego se manda a llamar sin parámetro, en la primera llamada la cadena queda como ABCM, pero cuando se hace la segunda llamada queda como ABCX.
## 13.	Respuesta C.
Se tienen que ejecutar los sout static (1 sola vez) luego por cada new (son 2) se tienen que ejecutar primero los bloques y después el constructor.
