# SudokuCompleto
En este sudoku se utilizan numeros del 1 al 9 para jugar.

Con el boton iniciar se inicializa el panel de juego, estableciendo el valor de ciertas celdas elegidas al azar 
basandose en una respuesta preestablecida por el creador del juego. Si el creador preestabece 
 A su vez, se inicializa un reloj 
compuesto por minutos y segundos, el cual contabilizara el tiempo que se tarde en finalizar el sudoku.

El panel inicial se conforma por algunas celdas vacias, las cuales podran ser modificadas seleccionando un boton
de la lista de botones que se encuentra por debajo del panel inicial y luego seleccionando la celda en la cual
se desea ubicar dicho valor. Existen tambien celdas con valores, las cuales no podran ser modificadas.

Para verificar si el valor que le dimos a una celda es correcto no hace falta realizar ninguna accion adicional,
al incertar el valor en la misma celda se corroborara. En el caso de que el valor de una celda no cumpla con 
alguna de las reglas del sudoku, se marcaran aquellas celdas que entren en conflicto con un fondo gris.

Para finalizar el sudoku de manera exitosa se debera haber completado el panel de juego en su totalidad
sin ningun error. Si se desea finalizar el sudoku de manera no exitosa se dera cerrar el frame principal,
en caso de querer reiniciar el juego, debera ser cerrado el frame principal y luego volver a correr el juego.
