# Pong Game

## Descripción del Proyecto

Este proyecto es una implementación del clásico juego Atari PONG utilizando la biblioteca `pygame` en Python. El objetivo es recrear el juego de PONG donde dos jugadores controlan paletas para golpear una pelota y evitar que salga del campo de juego.

## Objetivo del Programa

El objetivo del programa es permitir a los jugadores disfrutar de una versión digital del icónico juego PONG, con controles simples y una jugabilidad fluida. Este proyecto sirve como una introducción a la programación de videojuegos y el uso de la biblioteca `pygame`.

## Funcionalidades Principales

1. **Interfaz de Usuario**:
   - El juego se ejecuta en una ventana de `pygame` con una resolución de 1280x720 píxeles.
   - La interfaz muestra las paletas de los jugadores, la pelota y las puntuaciones.

2. **Controles del Jugador**:
   - El jugador controla la paleta derecha usando las teclas de flecha `ARRIBA` y `ABAJO` para mover la paleta hacia arriba y hacia abajo.
   - La paleta del oponente se mueve automáticamente siguiendo la posición de la pelota.

3. **Lógica del Juego**:
   - La pelota rebota en los bordes superior e inferior del campo de juego.
   - La pelota rebota en las paletas de los jugadores al ser golpeada.
   - Se incrementa la puntuación del jugador o del oponente cuando la pelota sale del campo de juego por el lado contrario.

4. **Actualización y Renderizado**:
   - El juego se actualiza a una velocidad de 300 fotogramas por segundo para garantizar una jugabilidad fluida.
   - Se actualizan las posiciones de la pelota y las paletas en cada fotograma.
   - Se renderizan las paletas, la pelota y las puntuaciones en la pantalla.

## Instrucciones de Ejecución

1. **Instalar Dependencias**:
   - Asegúrate de tener Python y `pygame` instalados en tu sistema. Puedes instalar `pygame` utilizando el siguiente comando: ```sh pip install pygame ```
2. **Ejecutar el Juego**: - Guarda el código del juego en un archivo, por ejemplo, `pong.py`. - Ejecuta el archivo utilizando Python: ```sh python pong.py ``` 
## Datos del Grupo – 
**Nombre del Proyecto**: El Impacto de las Nuevas Tecnologías en la Sociedad: Visualización del Futuro – 
**Integrantes del Grupo**: - Caroline Rashell Pauker Dominguez 

## Fecha – 

**Fecha de Creación**: 22 de diciembre de 2024 
