Conceptos básicos de JavaScript:

Variables:

Una variable es un elemento que se emplea para almacenar y hacer referencia a otro valor.

ejemplo: var nombre = 'Rodrigo'

Cada variable para ser realmente útil debe usarse con un operador:

1.- Asignación:

Guarda un valor específico en un variable. Ej: var número = 8

2.- Incremento y decremento:

Son útiles con variables numéricas y se utilizan para incrementar o decrementar en una unidad el valor de una variable.

Ejemplo:
var numero = 5;
++numero;
alert(numero);  // numero = 6


Strings:
Un String es una secuencia de caracteres que representan un valor.

Ejemplo: var saludo = 'Hola, como estas?'



Funciones:
Las funciones son herramientas que nos permiten manejar las variables.

Optimizan el código agrupándolo y que no haya necesidad de repetir código.

Se compone de una secuencia de declaraciones que forman el cuerpo de la misma. En la que se puede pasar valores y esta devolver un valor.

Para esto se utiliza retar y así la función nos arrojará un valor específico.

Por otro lado los argumentos son los parámetros de una llamada a la función, estos se pasan a las funciones por valor.

Ejemplo: 

Function nombrefuncion (argumento1, argumento2){
     Instrucciones 
}


Declaraciones 'if':

Son instrucciones del tipo "si se cumple esta condición, hazlo; si no se cumple, haz esto otro". También existen instrucciones del tipo "repite esto mientras se cumpla esta condición".

De esta manera los programas dejan de ser una sucesión lineal de instrucciones para convertirse en programas inteligentes que pueden tomar decisiones en función del valor de las variables.

'If' + 'else'

Diferencia:

'If' "si se cumple la condición, hazlo; si no se cumple, no hagas nada".

'If + else' "si se cumple esta condición, hazlo; si no se cumple, haz esto otro".




Valores Booleanos:

Esta variable almacena un tipo especial de valor que solamente puede tomar dos valores: true (verdadero) o false (falso). No se puede utilizar para almacenar números y tampoco permite guardar cadenas de texto.

Los únicos valores que pueden almacenar estas variables son true y false, por lo que no pueden utilizarse los valores verdadero y falso. 


Ejemplo:

var clienteRegistrado = false;
var ivaIncluido = true;

--