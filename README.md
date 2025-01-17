# CVU1R2

## José Carlos Duarte Vázquez
---

## Actividad 1: Curso de Junior Programmer.
1. [Lección 02 Jugabilidad Básica](https://github.com/CDuav/CVU1R2/blob/main/Lecciones/Lecci%C3%B3n%202.unitypackage)
2. [Lección 03 Sonidos y Efectos](https://github.com/CDuav/CVU1R2/blob/main/Lecciones/Lecci%C3%B3n%203.unitypackage)
3. [Lección 05 Interfaz de Usuario](#lección-05-interfaz-de-usuario)

## Actividad 2: Desafíos
1. [Desafío 1: Jugar a traer la pelota.](https://github.com/CDuav/CVU1R2/blob/main/Desafios/Desaf%C3%ADo%2001%20Jugar%20a%20la%20Pelota.unitypackage)
2. [Desafío 2: Bombas, Globos y Booleanos](https://github.com/CDuav/CVU1R2/blob/main/Desafios/Desaf%C3%ADo%2003%20Bombas%20Globos%20y%20Booleanos.unitypackage)
3. [Desafío 3: Aplasta Comida](https://github.com/CDuav/CVU1R2/blob/main/Desafios/Desaf%C3%ADo%2005%20Aplasta%20la%20Comida.unitypackage)

---

## Lección 02 Jugabilidad Básica
### Lección 2.1
El jugador podrá moverse de izquierda a derecha en la pantalla según las pulsaciones de las teclas izquierda y derecha del usuario, pero no podrá salir de la zona de juego por ningún lado.
### Lección 2.2
El jugador podrá pulsar la barra espaciadora y lanzar un proyectil Prefab a la Escena, el cual se destruirá cuando salga de los límites del juego. Los animales también se eliminarán de la Escena cuando abandonen los límites del juego.
### Lección 2.3
Cuando el usuario pulse la tecla S, un animal elegido al azar aparecerá en una posición aleatoria en la parte superior de la pantalla, caminando hacia el jugador.
### Lección 2.4
Los animales aparecerán en un intervalo de tiempo y caminarán por la pantalla, desencadenando un mensaje de «Game Over» si consiguen esquivar al jugador. Se destruirán si el jugador los golpea con un proyectil para alimentarlos.


## Lección 03 Sonidos y Efectos

### Lección 3.1
Se configurarán el personaje, fondo y obstáculo de tu elección. El jugador podrá presionar la barra espaciadora para hacer que el personaje salte mientras los obstáculos se generan en el extremo de la pantalla y bloquean el camino del jugador.
### Lección 3.2
El fondo se mueve sin errores en sincronía con los obstáculos y los obstáculos desaparecen cuando sobrepasan los límites del juego. Con el poder de la comunicación de scripts, el fondo y el Spawn Manager se detendrán cuando el jugador choque con un obstáculo. Chocar con un obstáculo también desencadenará un mensaje de fin del juego en el registro de la consola, lo cual detendrá el fondo y el gestor de generación.
### Lección 3.3
Con las animaciones del Animation Controller (Control de animación), el personaje tendrá 3 nuevas animaciones que ocurren en 3 estados diferentes del juego. Estos estados incluyen correr, saltar y morir, y se concatenan con transiciones suaves y se sincronizan para ajustarse al juego.
### Lección 3.4
La música se reproducirá mientras el jugador corre por la Escena dejando una estela de partículas de polvo a su paso. Un sonido de resorte se escuchará cuando salte y escucharemos un boom al chocar, lo cual creará una nube de partículas de humo mientras cae.

## Lección 05 Interfaz de Usuario
Descripción de las técnicas y herramientas para crear una interfaz de usuario efectiva.

### Lección 5.1
Tres objetivos buenos y un objetivo malo se generarán en una posición aleatoria en la parte inferior de la pantalla, los cuales se lanzarán por el aire con fuerza y torsión aleatorias. Estos objetivos se destruirán cuando el jugador haga clic en ellos o salgan del área activa.
### Leccion 5.2
Una sección «Score: » se mostrará en la interfaz de usuario y comenzará en 0. Cuando el jugador haga clic en el objetivo, el puntaje se actualizará y las partículas explotarán mientras se destruye el objetivo. Cada objetivo «Bueno» agrega un valor distinto al puntaje, mientras que un objetivo «Malo» reduce el puntaje.
### Lección 5.3
Cuando un objetivo «bueno» cae por debajo del sensor en la parte inferior de la pantalla, los objetivos dejarán de generarse y un mensaje de «Game Over» se mostrará en la pantalla. Bajo el mensaje de «Game Over» habrá un botón «Reset Game» que reiniciará el juego y el puntaje para que el jugador pueda disfrutarlo nuevamente desde el principio.
### Lección 5.4
Al iniciar el juego se abrirá un hermoso menú donde se mostrará el título de forma prominente y tres botones de selección de dificultad en la parte inferior de la pantalla. Cada dificultad afectará el ritmo en que se generen los objetivos, lo cual exigirá tener mayor habilidad para evitar que los objetivos «buenos» caigan.

---

## Desafío 1: Jugar a traer la pelota.
- Se genera una bola aleatoria (de 3) en una posición X aleatoria sobre la pantalla.
- Cuando el usuario pulsa la barra espaciadora, aparece un perro que corre para atrapar la pelota.
- Si el perro se encuentra con la pelota, esta se destruye.
- Si la pelota toca el suelo, se muestra un mensaje de depuración «Game Over».
- Los perros y las pelotas se eliminan de la Escena cuando salen de la pantalla.

## Desafío 2: Bombas, Globos y Booleanos
- El globo flota hacia arriba cuando el jugador mantiene presionada la barra espaciadora.
- El fondo se repite sin errores y simula el movimiento del globo.
- Se generan bombas y tokens monetarios de manera aleatoria a intervalos.
- Cuando colisionas con los tokens monetarios, hay un efecto de sonido y partículas.
- Cuando colisionas con la bomba, hay una explosión y el fondo se detiene.

## Desafío 3: Aplasta Comida
- Todos los botones se ven bien con el texto alineado correctamente.
- Cuando seleccionas una dificultad, la frecuencia de generación cambia según corresponde.
- Cuando haces clic en una comida, se destruye y el puntaje se actualiza en la parte superior izquierda.
- Cuando pierdes el juego, aparece un botón de reiniciar que te permite jugar de nuevo.
