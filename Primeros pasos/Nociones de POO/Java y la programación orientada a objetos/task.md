# Java y la Programación Orientada a Objetos

Hasta ahora, en la materia, hemos estado trabajando bajo el paradigma de la programación estructurada (y lo seguiremos haciendo). Sin embargo, no es el único paradigma de programación que existe.

Hoy en día, uno de los paradigmas más usados es el *orientado a objetos* (POO). Esta metodología es inseparable del lenguaje de programación Java, y todos los programas de Java son, hasta cierto punto, orientados a objetos. Debido a la importancia de la programación orientada a objetos para Java, resulta útil comprender los principios básicos de la POO antes de escribir incluso el programa más simple de Java.

En clases anteriores, vimos que la programación estructurada se caracteriza, entre otras cosas, por sus estructuras de control y la independencia de la instrucción GOTO. Aunque este paradigma constituye una herramienta poderosa, alcanza un límite cuando un proyecto se vuelve demasiado grande.

En cada momento clave del desarrollo de la programación, se crearon técnicas y herramientas que permitieron al programador lidiar con una complejidad creciente. Antes de la programación orientada a objetos, muchos proyectos estuvieron cerca del punto en el cual el paradigma estructurado ya no funcionaba.

La POO retomó las mejores ideas de la programación estructurada y las combinó con varios conceptos nuevos. El resultado fue una nueva manera de organizar un programa.

## Distintas formas de organizar un programa

En el sentido más general, un programa puede organizarse de una de las siguientes maneras:

- Alrededor de su código (lo que está sucediendo).
- Alrededor de sus datos (lo que se está afectando).

Si usamos exclusivamente el paradigma de la programación estructurada, los programas se encontrarán típicamente organizados alrededor de su código. Es decir son "códigos que actúan sobre los datos".

Los programas orientados a objetos funcionan de manera diferente: están organizados alrededor de los datos y el principio clave es que "los datos controlan el acceso al código". En un lenguaje orientado a objetos, nosotros definimos los datos y las rutinas que permiten actuar sobre esos datos. Por lo tanto, un tipo de dato define de manera precisa el tipo de operaciones que puede aplicarse a esos datos.

De manera muy resumida, podemos pensar a la programación orientada a objetos como una extensión de la programación estructurada en la cual adoptaremos un enfoque ligeramente diferente para escribir programas. Escribir un programa orientado a objetos implicará:

- Crear clases, que serán planos de objetos.
- Crear objetos que son instancias específicas de esas clases.
- Crear aplicaciones que manipulen o utilicen esos objetos.