# Inicializar variables

Guardar un valor en una variable es lo que se denomina **asignar**. Por otro lado, la **inicialización** de variables es el proceso de asignar un valor **inicial** a una variable. Este paso es muy importante, ya que Java no tolera operaciones con variables no inicializadas.

## Asignación

Para asignar un valor a una variable es estrictamente necesario que la variable haya sido previamente declarada. Luego, la sintaxis para almacenar un valor es la siguiente:

```
<identificador> = <valor>;
```

El operador `=` se denomina *comando de asignación* porque permite asignar valores a variables.

A modo de ejemplo, observe las instrucciones de las líneas 11 a 14 donde se inicializan las variables declaradas anteriormente.

> 🔎 **Observaciones**
>  - Los valores de punto flotante utilizan el punto `.` como separador decimal.
>  - Los caracteres deben escribirse entre comillas simples `' '`.

### Inicialización inmediata

Es posible inicializar una variable en la misma instrucción en la que se declara. A modo de ejemplo, observe la instrucción de la línea 16: la sentencia
```java
int promocion = 2024;
```
tiene el mismo efecto que las instrucciones:

```
int promocion;
promocion = 2024;
```