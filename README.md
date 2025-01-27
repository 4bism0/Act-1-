# Act-1-
# Tic-Tac-Toe (Juego del Gato)

Este proyecto es una implementación en C# del juego gato. Permite que dos jugadores participen turnándose para colocar sus símbolos en una cuadrícula de 3x3 hasta que haya un ganador o el juego termine en empate.

## Características

- **Juego interactivo para 2 jugadores**: Cada jugador puede ingresar su nombre.
- **Validación de entradas**: Se asegura que las elecciones sean válidas y no se sobreescriban posiciones ocupadas.
- **Tablero dinámico**: Se actualiza y muestra en cada turno.
- **Detección de ganador o empate**: Identifica automáticamente si un jugador ha ganado o si el juego termina en empate.

## Estructura del Código

1. **Inicialización**:
   - Se define un tablero representado como un array de cadenas `string[] grid` con valores iniciales del 1 al 9.
   - Se solicita a los jugadores que ingresen sus nombres.

2. **Flujo principal del juego**:
   - El juego se desarrolla en un bucle que alterna turnos entre los jugadores.
   - Cada jugador elige una posición del tablero donde colocar su símbolo (`X` o `O`).
   - Se valida la elección antes de actualizar el tablero.

3. **Comprobación de condiciones**:
   - Se verifica si un jugador ha ganado comparando las combinaciones del tablero con patrones predefinidos.
   - Se detecta un empate si se completan los 9 turnos sin un ganador.

4. **Funciones auxiliares**:
   - `MostrarTablero`: Muestra el tablero actualizado en cada turno.
   - `HayGanador`: Determina si existe una combinación ganadora en el tablero.

## Cómo Ejecutarlo

1. Compila el código usando un compilador C# (por ejemplo, Visual Studio o `dotnet` CLI).
2. Ejecuta el programa en un entorno de consola.
3. Sigue las instrucciones en pantalla para ingresar los nombres de los jugadores y jugar.

