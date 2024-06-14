# Definición de una clase

En Java, la sintaxis del lenguaje está diseñada de tal manera que **todo el código debe estar contenido dentro de una clase**. Esto es una convención del lenguaje y una parte integral de su diseño.


Junto con esta tarea se incluye un archivo de código fuente llamado `PrimerPrograma.java` que servirá de ejemplo para analizar como se define una clase.

## Paquetes

La primera línea de código es:
```java
package  core;
```
Esta línea corresponde a la declaración del **paquete** al que pertenece la clase (La clase pertenece al paquete core). En Java, un "paquete" es una forma de organizar y gestionar conjuntos de clases y otros elementos relacionados. En líneas generales, es básicamente un directorio en el sistema de archivos que contiene archivos, idéntico a una carpeta.

Los paquetes ayudan a evitar conflictos de nombres y facilitan la organización del código. Permiten agrupar clases que tienen funcionalidades similares o están relacionadas de alguna manera. Además, como veremos en la unidad 4, los paquetes permiten gestionar el control de acceso de los elementos que están en ellos.

## Definición de la clase
La siguiente instrucción luego de la declaración del paquete es la definición de la clase `PrimerPrograma`. Esta declaración consiste en la sentencia: `public class PrimerPrograma` seguída de unas llaves que abren y cierran (`{}`). Cada uno de estos términos se analizan a continuación.

### Análisis de la declaración de la clase

#### `public`

La definición de la clase arranca con la palabra reservada `public`. Esta palabra clave es un *modificador de acceso*, tema que trataremos en profundidad en la unidad 4. Sin embargo, para dar una explicación breve, el hecho de que la clase sea pública implica que es accesible desde cualquier otro lugar, ya sea dentro del mismo paquete o desde otro paquete.

#### `class`

Es la palabra clave que se utiliza para definir una clase en Java.

#### `PrimerPrograma`

Este es el nombre de la clase que se está definiendo. En Java, las convenciones de nomenclatura sugieren que los nombres de las clases deben seguir el estilo de PascalCase, donde cada palabra comienza con mayúscula y no se utilizan espacios ni caracteres especiales.

> ⚠️ **El nombre de la clase debe coincidir con el nombre del archivo .java.**
> Esto es necesario porque otras clases que deseen utilizar esta clase pública necesitarán saber cómo encontrarla en el sistema de archivos.

> ⚠️ **Java es sensible a minúsculas y mayúsculas.**
> Esto implica que hay que prestar atención al utilizar palabras claves, escribiéndolas de la forma correcta según la sintaxis de Java.