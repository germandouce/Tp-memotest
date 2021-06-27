# Tp-memotest
Un memotest con tematica de quimica con algunas modificaciones.
Se juega desde la terminal.

## Reglas
Cada jugador tiene un tablero que tiene N fichas distribuidas en M filas y M columnas de las cuales se desconoce su contenido hasta darlas vuelta, pero siempre se sabe que hay 2 fichas de cada tipo. Los jugadores deberán encontrar los pares de fichas idénticos en su tablero. En caso de no encontrarlos las fichas volverán a su posición oculta original. En caso de acertar y encontrar el jugador puede volver a jugar en el mismo turno, intentando ubicar otro par. La partida termina una vez que todos los pares de un tablero son descubiertos y el ganador será el jugador que lo haga primero. 

Los niveles de duración son corto, medio y largo. La duración estará representada con la cantidad de filas y columnas presentes en el tablero y se podra elejir en el menu principal:
* Corto: 4x4 
* Medio: 8x8 
* Largo: 12x12

# Las fichas
Las fichas que pueden aparecer en cada tablero de manera aleatoria exactamente 2 veces son los siguientes elementos de la tabla periodica:

'H', 'He', 'Li', 'Be', 'B', 'C', 'N', 'O', 'F', 'Ne', 'Na', 'Mg', 'Al', 'Si', 'P', 'S', 'Ar', 'K', 'Ca', 'Sc', 'Ti', 'U', 'Y', 'Rf', 'V','Cr', 'Mn', 'Fe', 'Co', 'Ni', 'Cu', 'Zn', 'Ga', 'Ge', 'As', 'Se', 'Br', 'Kr', 'Rb', 'Sr', 'Cl', 'Ru', 'Ag', 'Cd', 'In', 'Sn', 'Sb', 'Te',  'I', 'Xe', 'Cs', 'Ba', 'Ce', 'Pr', 'Nd', 'Pm', 'Sm', 'Eu', 'Gd', 'Lu', 'Pt', 'Au', 'Hg', 'Pb', 'Bi', 'Po', 'Rn', 'Fr', 'Ra', 'Zr', 'Np','Es'

## Cartas especiales
Al llegar un turno al jugador, existe la posibilidad de que se obtenga o no una carta especial en base a probabilidades que se definen en el menú. Por turno solo sale como máximo 1 carta especial. Las cartas espciales son:

1. Carta Replay: Permite hacer un intento más durante el turno. 
2. Carta Layout: Redistribuye todas las fichas del tablero del jugador que la tiene de 
manera aleatoria 
3. Carta Toti: Espeja el tablero del jugador que la tiene de forma azarosa, puede ser 
horizontal o vertical. 
4. Carta Fatality: Traspone el tablero del jugador que la tiene

El jugador puede decidir jugar su carta especial en dicho turno o guardarla para otro turno. Se pueden acumular más de una carta especial de cada tipo

## Scores
Como último detalle, el juego permite guardar (temporalmente, es decir durante la ejecucion del programa) el score de todas las partidas jugadas, ordenadas por quien gano mayor cantidad.

## Futuras versiones
Comming soon...
* Al elejir una ficha se le dirá al jugador el nombre del elemento elegido.
* Se podran guardar y editar los scores en un archivo .csv o .txt para que no se eliminen al cerrar el juego.
