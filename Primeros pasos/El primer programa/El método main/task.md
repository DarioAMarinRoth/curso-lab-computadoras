# El método *main*

Contar con una clase no es suficiente para poder escribir un programa ejecutable. Java requiere que la clase donde estará el código ejecutable cuente con una estructura específica denominada *método main*.

El método main es el punto de entrada de un programa Java. Es el método que se ejecuta cuando inicias un programa Java desde la línea de comandos utilizando el comando `java`. Específicamente, el lenguaje está diseñado para que ante la orden de ejecución de un archivo de clase, la JVM (Java Virtual Machine) busca un método main dentro de esa clase para comenzar la ejecución del programa. Si encuentra un método main con la firma correcta, comienza la ejecución del programa, invocando este método. Si la JVM no encuentra un método main válido en la clase especificada, muestra un mensaje de error indicando que no se puede encontrar el punto de entrada del programa.

## Declaración del método main

En la línea 4 del archivo PrimerPrograma.java se encuentra la declaración del método main. Notarás que a diferencia del programa de la tarea anterior, este tiene un ícono de ejecución tanto en la declaración de la clase como en la definición del método main (lo que indica que el programa se puede ejecutar).

El método main debe escribirse siempre de la misma manera, tal como aparece en la línea 4: `public static void main(String[] args)`.

> 🚀 El método main se puede escribir rápidamente escribiendo sus iniciales `psvm` y a continuación pulsando la tecla `TAB`.

Al igual que una clase, el cuerpo del método main queda delimitado por llaves (`{}`). Todo el código que debe ejecutarse al comenzar el programa deberá estar escrito entre estas llaves.
 
También es importante notar que el método main esta indentado un nivel con respecto a la declaración de la clase debido a que este está dentro de la clase.

### Análisis de la declaración del método main

El significado de los elementos que participan en la declaración del método main no son fáciles de entender cuando recién nos introducimos al lenguaje Java. Se puede seguir perfectamente el desarrollo de este curso sin profundizar en lo que se explicará a continuación, siempre y cuando se haya entendido que todo programa ejecutable debe contar con un método main.

#### `public`

Al igual que la clase, el método main lleva el modificador de acceso `public`, lo que, como visto anteriormente, implica que es accesible desde cualquier otra clase en el mismo paquete, así como desde clases fuera del paquete donde se encuentra la clase que contiene el método main.

#### `static`

La palabra `static` es un modificador que hace que el método a la clase en sí misma y no a objetos que se instancien de ella.

#### `void`

Este es el tipo de retorno del método main. Veremos tipos de retorno más adelante en esta misma unidad. En líneas generales significa que el método no devuelve ningún valor específico luego de su ejecución.

#### `main`

Este es el nombre del método. En Java, el método main es un nombre especial y convencional para el punto de entrada de un programa.

#### `String[] args`
Estos son los parámetros que recibe el método main. En este caso, args es un array del tipo `String` que contiene los argumentos pasados al programa desde la línea de comandos cuando se ejecuta
