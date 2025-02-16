# TIPOS DE DATOS EN JAVA

## JVM
* Realiza una gestion eficiente de la memoria 
* Distribuye en dos zonas : Stack(Pila) y heap(Monton)

![RAM](/modelo/modelo/ram.jpeg "RAM") 

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
* Accesible desde otras instancias de clase
* Su ciclo de vida termina cuando no se necesita mas
* Mientras exista al menos una referencia activa en la zona de datos esta se mantendrá.
* Tan pronto como no haya mas referencias, la zona se considera no utilizada y se procede a su destruccion por parte de el Garbage Collector.
* Un tipo referenciado puede no referenciar nada -> null
* new: instanciacion de una clase. Reserva una direccion de un área de memoria.

## Variable de referencia
* Caracteriza una instancia de clase, es decir la direccion donde está el objeto.
* Contiene la direccion de un objeto, cuyo valor por defecto es null.
* Durante una prueba e igualdad entre dos variables por referencia, son las direcciones de los objetos lo que compara, y no el contenido de los objetos en si mismos.
* Cuando se usa una referencia como argumento de un método es la direccion del objeto lo que se pasa, y no el objeto en si mismo.


