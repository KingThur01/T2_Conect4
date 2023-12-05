# T2_Conect4

Lógica del juego
Jugador Humano
El jugador humano realiza movimientos eligiendo la columna donde desea colocar su ficha.
Se muestra el estado actual del tablero después de cada movimiento.
El juego continúa hasta que un jugador conecta cuatro fichas o el tablero se llena.
Jugador IA (Algoritmo Minimax)
La IA utiliza el algoritmo Minimax para tomar decisiones.
El árbol de juego representa todas las posibles combinaciones de movimientos y contramovimientos.
Cada nodo del árbol representa un estado del tablero y tiene un valor asignado mediante la función de evaluación.
La IA selecciona el movimiento que maximiza su puntuación, asumiendo que el oponente también juega de manera óptima.
Algoritmo Minimax
El algoritmo Minimax es un algoritmo de búsqueda en árboles de juegos para juegos de dos jugadores de suma cero con información perfecta, como el ajedrez o el Conecta 4. La idea principal es explorar recursivamente todas las posibles jugadas hasta una cierta profundidad y asignar valores a los nodos terminales mediante una función de evaluación.

Minimización y Maximización: El jugador activo intenta maximizar el resultado, mientras que el oponente intenta minimizarlo.
Recursividad: La búsqueda se realiza de manera recursiva, explorando todas las combinaciones posibles.
Poda Alfa-Beta: Se utiliza para eliminar nodos innecesarios y mejorar la eficiencia del algoritmo.
En el contexto de Conecta 4, la función de evaluación podría asignarse basándose en la presencia de fichas propias y del oponente en líneas posibles.

Este proyecto implementa el algoritmo Minimax en la clase ArbolJuegopara permitir que la IA tome decisiones informadas y desafiantes.
