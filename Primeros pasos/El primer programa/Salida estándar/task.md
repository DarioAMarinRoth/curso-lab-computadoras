
# La salida estándar

En Java, la salida estándar es la consola o terminal donde se muestran los mensajes impresos por un programa en ejecución. Es comúnmente utilizada para mostrar mensajes, resultados de cálculos y para depuración.

## Acceso a la salida estándar

Cómo hemos visto anteriormente, todas las acciones en Java son ejecutadas, en su mayoría por objetos. La impresión de mensajes no es la excepción. 

Las acciones que un objeto puedo realizar se denominan **métodos**. Cuando queremos que un objeto realice una acción se dice que **invocaremos** o llamaremos a un método. La sintaxis para invocar a un método de un objeto es la siguiente:

```
<objeto>.<método>(<argumento_1>, <argumento_2>, ... , <argumento_n>);
``` 
> 🔎 **Observación:**
> Notará que el llamado a un método debe finalizar con un punto y coma (`;`). En java, el punto y coma se utiliza para indicar el final de una instrucción y es necesario incluirlo.

Los **argumentos** de un método son los valores que se pasan a un método cuando este es llamado. Estos argumentos permiten que el método realice su función con datos específicos proporcionados en cada llamada. En términos más simples, los argumentos son la información que le damos a un método para que pueda realizar su función.

Estos argumentos deben ir encerrados paréntesis y separados por coma (en el caso de tener más de uno). Si el método en cuestión, no necesita argumentos, entonces los paréntesis se escriben igualmente sin colocar nada dentro de ellos.

Para imprimir un mensaje por la salida estándar será necesario utilizar el objeto `System.out` y algunos de sus métodos principales: `print`, `println` o `printf`. Por el momento, nos centraremos en los dos primeros. Ambos tienen un único argumento (el mensaje que se desea imprimir). A continuación se detalla el funcionamiento de cada uno.

### El método `print()`

El método `print` permite imprimir un mensaje en la consola sin agregar una nueva línea al final. Esto significa que la siguiente salida continuará en la misma línea. Es útil cuando se desea una salida continua en una misma línea.

A modo de ejemplo, en el archivo `PrimerPrograma.java`, de las líneas 6 a la 9, hay 4 instrucciones de impresión de mensajes utilizando el método `print`. Ejecute el programa (haciendo clic en el triángulo verde o pulsando la combinación de teclas `Shift + F10`). Verá que a pesar de haber cuatro mensajes, todos se imprimen en el mismo renglón de la consola, formando la oración *"Laboratorio de computadoras electrónicas"*.

> 🔎 **Observación:**
> Si el mensaje contiene texto, el mismo deberá escribirse entre comillas dobles.

### El método `println()`

El método `println` es similar a `print`, pero añade una nueva línea después de imprimir el texto. Esto asegura que cualquier salida posterior aparezca en una nueva línea, facilitando la lectura.

A modo de ejemplo, en el archivo `PrimerPrograma.java`, de las líneas 11 a la 15, hay 5 instrucciones de impresión de mensajes utilizando el método `println`. Si ya ejecuto el programa, verá que cada uno de estos mensajes se imprimieron en una línea diferente. También notará que el método en la línea 11 no tiene argumentos. Esto es así, para que simplemente se genere un salto de línea en la consola sin mostrar ningún mensaje. De no hacerlo, el mensaje de la instrucción 12 se mostraría en la misma línea que el mensaje de la instrucción 9. Borre la instrucción 11 y ejecute el programa si desea ver los efectos.

> 🚀 Una instrucción `println` se puede colocar rápidamente escribiendo `sout` y a continuación pulsando la tecla `TAB`.

## Caracteres especiales

Un carácter especial es aquel que tiene un significado especial para el compilador. Estos no se interpretan de la misma manera que los caracteres regulares y, en su lugar, desencadenan acciones o comportamientos especiales.

En Java, así como en muchos otros lenguajes de programación, hay varios caracteres especiales que se utilizan para representar acciones o formatos específicos dentro de cadenas de texto u otros contextos. Los más comunes son los siguientes:

- `\n`: **Nueva línea**. Se utiliza para indicar un salto de línea en el texto.
- `\t`: **Tabulación**. Inserta un carácter de tabulación en el texto.
- `\b`: **Retroceso**. Borra el carácter anterior en el texto.
- `\r`: **Retorno de carro**. Mueve el cursor al principio de la línea actual.
- `\\`: **Barra invertida**. Se utiliza para escapar caracteres especiales en una cadena.
- `\'`: **Comilla simple**. Se utiliza para representar una comilla simple dentro de una cadena.
- `\"`: **Comilla doble**. Se utiliza para representar una comilla doble dentro de una cadena.
- `\uXXXX`: **Representación Unicode**. Permite incluir caracteres Unicode en una cadena, donde `XXXX` es el valor hexadecimal del código Unicode del carácter.

---

## Resumen de clases utilizadas y enlaces a la documentación oficial

### Clase System

Clase en Java que proporciona acceso a varias funciones y propiedades del sistema. No puedes crear una instancia de esta clase, pero puedes acceder a sus miembros estáticos.

### Objeto out
Objeto del tipo `PrintStream` que está dentro de la clase `System`. Representa la salida estándar del programa.

### Documentación oficial

- [Clase System](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/System.html)
- [Clase PrintStream](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/PrintStream.html)
