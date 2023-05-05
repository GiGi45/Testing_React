# Tic-Tac-toe

## UseState
El import usado es el "useState", es una funcion especial de React que permite conectarse a las caracteristcias de React

## Function Square()
Crea un boton dandole como parametros un valor y la funcion onSquareClick(), el cual se usara mas adelante

## Board()
Tiene 3 parametros de entrada. Da forma al juego, creando los botones y accediendo a ellos para modificarlos cuando sean presionados.

## handleClick()
Recibe como parametro al iterador. Con este se controlan los movimientos que realizan los jugadores. Verifica si existe un ganador o a quien le toca el siguiente turno

## Game()
Esta funcion va guardando el estado en el que esta el juego en todo momento.

## handlePlay()
Almacena las jugadas dentro del array history.

## jumpTo()
Cambia el estado de los movimientos para poder seguir con el juego

## calculateWinner()
Se controlan los movimientos de los jugadores. Ademas, se determina quien es el ganador del juego.
