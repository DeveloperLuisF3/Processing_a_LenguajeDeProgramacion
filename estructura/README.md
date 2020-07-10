# 2. Estructuras: Elementos del Código

## Elementos que se introducen en esta Unidad:

* // (comentario)
* /* */ (comentario multilinea)
* ; (terminador de acción)
* , (coma)
* print()
* printl()

El hecho de crear un programa implica recurrir a la escritura y aprender un lenguaje. Similar a cuando aprendemos un nuevo lenguaje oral o escrito, necesitamos aprender una sintaxis y una lógica. Escribir en un lenguaje humano es muy complicado. Posee ambigüedad en las palabras, y mucha flexibilidad para la construcción de párrafos. En ese sentido, el lenguaje de máquina es más sencillo, pero posee una dificultad clara: la lógica de la programación. Usualmente, un ser humano puede percatarse de un error de sintaxis y darlo por alto, restándole parcial o completa importancia. Sin embargo, en un lenguaje de máquina las cosas son de una forma o de otra: O está bien, o está mal.

## Comentarios

Los comentarios son ignorados por los ordenadores, pero son **muy importantes** para los humanos. Processing permite agregar notas en cualquier sector del código. Pueden ser de solo una linea o de muchas líneas. Ya que los programas usan signos muy arcaicos y de difícil identificeción, muchas veces es complicado recordar que hacía cada sector individualmente. Por lo tanto se recurre a la utilidad del comentario, muy útil a la hora de revisar el código, ya sea por el propio programador como por otros. El siguiente programa explica, por sí solo, como se comenta:

```processing
    // Dos barras laterales son usadas para comentar
    // Todo el texto en la misma línea es parte de un comentario
    // No debe haber espacio entre las barras, por ejemplo "/ /", de lo contrario
    // el comentario no funcionará.

    // Si desea muchas líneas
    // lo ideal es usar el método multilinea.

    /*
    Una barra lateral seguida por un asterisco
    permite el comentario de multilinea.
    */
```