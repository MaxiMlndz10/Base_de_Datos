## Práctica 4.
### Introducción a SQL
Objetivo: Demostrar la correcta identificación de los conceptos del lenguaje SQL
Ejercicio:

1. Menciona los comandos DMl: (valor .85)
 * SELECT
 * INSERT
 * UPDATE
 * DELETE

2. Menciona 3 tipos de datos que existen: (valor .85)
 * CHAR
 * VARCHAR
 * FLOAT

3. ¿Qué diferencia existe entre TRUNCATE y DELETE?(valor .85)
 * TRUNCATE:
    * Es una operación DDL.
    * No permite el borrado selectivo (TRUNCATE TABLE elimina todo el contenido de la tabla).
    * No se puede ejecutar, si la tabla tiene asociadas, aun si no existen registros en la tabla que contiene la FK.
    * Es la forma más rapida de eliminar el contenido de una tabla.
  
 * DELETE:
    * Es una operación DML.
    * Permite el borrador selectivo mediante la clausula WHERE.
    * Se puede ejecutar si hay FK asociadas a la tabla, pero siempre y cuando no tengan registros asociados o la FK este deshabilitada.
    * Es mas lenta.

4. ¿Para qué se utiliza el atributo UNIQUE?(valor .85)
   R= Para garantizar que no se inserten valores duplicados en una columna específica o combinación de columnas que participen en la restricción UNIQUE y no formen    parte de la CLAVE PRIMARIA.


5. ¿Qué diferencia hay entre los tipos de datos VARCHAR y CHAR? (valor .85)


6. Defina brevemente el significado de las siglas SQL(valor .85)


7. Defina brevemente qué es MySQL WorkBench (valor .85)

## Práctica 5.
### Gestores de base de datos

Objetivo: Categorizar los distintos gestores de base de datos que existen y señalar las
ventajas y desventajas

Evaluación: Conoce los tipos de gestores de base de datos 3 puntos.

Domina sus diferencias de los gestores de base de datos mencionados 3 puntos

Ejercicio:

En un mapa conceptual presenta 3 gestores de bases de datos, sus características
principales, las ventajas y desventajas. (valor 6)

![image](https://user-images.githubusercontent.com/91554777/170415427-e2b7321b-a97f-43b0-ac24-6e506c307e6b.png)


![gestor base de datos](https://user-images.githubusercontent.com/101481300/171969076-a7d83344-21da-42c2-bfa4-4c456369dc9f.png)


## Práctica 6.
### Herramienta en línea y ejercicio necesarios para realizar las prácticas

Creación de base de datos.

Objetivo: Demostrar mediante la creación de una base de datos el uso y la aplicación de
las funciones

Ejercicio: Creación de la base de datos (valor 18 puntos)

Tienda de informática

![image](https://user-images.githubusercontent.com/91554777/170415101-717bca19-3644-46a9-8a57-8d5940c5d283.png)




Modelo entidad/relación




Base de datos para MySQL
