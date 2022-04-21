# TIPOS DE DATOS EN JAVA

## JVM
* Realiza una gestion eficiente de la memoria 
* Distribuye en dos zonas : Stack(Pila) y heap(Monton)

![RAM](/modelo/ram.jpeg "RAM") 

## Stack
* se almacenan: variables locales, llamadas a metodos (parametros y resultados), variables primitivas, referencia a objetos del heap 
* Memoria estatica
## Heap
* Gestionado por el Garbage collector.
* Espacio de memoria en tiempo de ejecucion donde se registran los objetos.
* Memoria dinamica.
* No posee estructura de asignacion de espacios.

## VARIABLE
* contenedor de memoria donde se almacena informacion.
* En java se declaro por un tipo que se conserva durante todo su ciclo de vida en el interior de la app.
* Existen de tipo primitivo y referenciado.

## Primitivos 
* Contenedor de tamaño especifico que almacenan valores y no tiene metodos.
* Ejemplo: boolean, char , byte , short, long, float, double.

## Referenciados
* Almacenan las referencias a los datos.
* Estos datos se escriben en una zona de memoria llamada heap.

