# Strings

En Java, el texto se maneja mediante un tipo especial llamado String. Aunque String **no es un tipo de dato primitivo** como si lo puede ser `int` o `double` sino que es una clase. Sin embargo, Java la trata de manera especial debido a su uso frecuente lo que permite usarla de una manera muy simple, casi como si fuera un tipo primitivo.

## Variables del tipo String

La manera más sencilla de crear un String es usando un *literal String*. La sintáxis es idéntica a la de la declaración de una variable de un tipo primitivo:

```
String <identificador>;
```

A modo de ejemplo, en la línea 6, se declara un variable de tipo String cuyo identificador es "nombre".

> ⚠️ **Cuidado**: String, al ser una clase y no un tipo de dato primitivo comienza con mayúscula.

## Asignar un String

Nuevamente, la operación de asignar un valor a un String es idéntica a la de asignar un valor a cualquier variable que hemos visto anteriormente. Solamente se debe tener la precaución de que a un String solo se le puede asignar texto, por lo tanto, el valor asignado debe estar entre comillas dobles `" "`.

```
<identificador> = "<valor>";
```

A modo de ejemplo, en la línea 7 se asigna el texto "Fulano" a la variable `nombre`.

### Inicialización inmediata

Al igual que con los tipos primitivos, también es posible asignar un valor a un String en la misma línea que se está declarando. La sintaxis es la siguiente:
```
String <identificador> = "<valor>";
```
A modo de ejemplo, observe la instrucción de la línea 9.

## Concatenar Strings
Uno de los aspectos más importantes y útiles de trabajar con String en Java es la capacidad de concatenar cadenas de texto. Concatenar String significa unir dos o más cadenas de texto en una sola.

La forma más sencilla y común de concatenar String en Java es usando el operador `+`. Este operador te permite unir dos String de manera directa.

```text
String1 + String2 + String3 + ... + StringN;
```

A modo de ejemplo, en la línea 11 se concatenan 3 Strings para imprimir por la consola un mensaje más complejo (puede correr el código si lo desea). Los Strings concatenados son:

- `nombre`: que contiene la cadena `"Fulano"`.
- Un espacio en blanco `" "` que no ha sido asignado a ninguna variable.
- `Apellido`: que contiene la cadena `"De tal"`.

El resultado final de la concatenación es el String `"Fulano De Tal"`.

### Concatenación y números

Java permite concatenar String con otros tipos de datos, como números. Cuando concatenas un String con un número, el número se convierte automáticamente en texto.