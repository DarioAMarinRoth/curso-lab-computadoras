# Variables

En la unidad anterior vimos que una variable es un espacio de memoria a la cual le asignamos un identificador donde podemos almacenar un dato. Una variable puede almacenar únicamente un valor a la vez, pero podemos modificar este valor tantas veces como se desee.

## Tipos de datos

Los tipos de datos son una clasificación de datos que informa al compilador o al intérprete sobre cómo el programador pretende utilizar los datos. Los tipos de datos definen las operaciones que se pueden realizar sobre los datos, la forma en que se almacenan y la forma en que se interpretan.

Java es un lenguaje **fuertemente tipado**. Esto implica que se aplican reglas estrictas sobre cómo se pueden usar y combinar diferentes tipos de datos. En un lenguaje fuertemente tipado, las conversiones automáticas entre tipos son limitadas o no permitidas, lo que obliga a los programadores a ser explícitos sobre cómo se deben tratar los tipos de datos en su código. Esto generalmente ayuda a evitar errores que pueden surgir de conversiones implícitas no deseadas.

A continuación, se presenta una tabla con los tipos de datos primitivos presentes en java:

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tipos de Datos Primitivos en Java</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
<table>
    <tr>
        <th>Tipo de Dato</th>
        <th>Descripción</th>
        <th>Tamaño (bits)</th>
        <th>Rango</th>
    </tr>
    <tr>
        <td>byte</td>
        <td>Entero con signo de 8 bits</td>
        <td>8</td>
        <td>-128 a 127</td>
    </tr>
    <tr>
        <td>short</td>
        <td>Entero con signo de 16 bits</td>
        <td>16</td>
        <td>-32,768 a 32,767</td>
    </tr>
    <tr>
        <td>int</td>
        <td>Entero con signo de 32 bits</td>
        <td>32</td>
        <td>-2<sup>31</sup> a 2<sup>31</sup>-1</td>
    </tr>
    <tr>
        <td>long</td>
        <td>Entero con signo de 64 bits</td>
        <td>64</td>
        <td>-2<sup>63</sup> a 2<sup>63</sup>-1</td>
    </tr>
    <tr>
        <td>float</td>
        <td>Número en punto flotante de precisión simple</td>
        <td>32</td>
        <td>~1.4e-45 a ~3.4e+38</td>
    </tr>
    <tr>
        <td>double</td>
        <td>Número en punto flotante de precisión doble</td>
        <td>64</td>
        <td>~4.9e-324 a ~1.8e+308</td>
    </tr>
    <tr>
        <td>char</td>
        <td>Carácter Unicode de 16 bits</td>
        <td>16</td>
        <td>'\u0000' a '\uffff' </td>
    </tr>
    <tr>
        <td>boolean</td>
        <td>Valor lógico</td>
        <td>1</td>
        <td>true o false</td>
    </tr>
</table>

</body>
</html>

En la materia, normalmente utilizaremos los siguientes tipos de datos:
- **int:** para números enteros.
- **double:** para números que posean parte decimal no nula.
- **char:** para caracteres.
- **boolean:** para valores lógicos.

## Declaración de variables

Para declarar una variable en Java, debe utilizarse la siguiente sintaxis:
```text
<tipo de dato> <identificador>;
```

En el código fuente de esta tarea, se muestran ejemplos de declaraciones de variables de las líneas 6 a 9.

Java es un lenguaje fuertemente tipado, es decir, uno en el cual cada variable tiene un tipo de dato bien definido que limita las operaciones que puedes realizar con ella; el tipado fuerte implica que todas las variables deben ser declaradas antes de que puedan ser usadas. Es posible declarar una variable en cualquier punto antes de usarla, pero es práctica común declarar las variables en la parte superior del método y colocar las sentencias ejecutables después de las declaraciones.

## Identificadores

Los nombres de variables deben ser identificadores legales de Java. Básicamente, un nombre de variable debe comenzar con una letra, no puede contener espacios y no puede ser una palabra reservada. Convencionalmente, los nombres de las variables comienzan con letras minúsculas y se capitalizan las palabras subsiguientes dentro del identificador (nomenclatura camelCase).
