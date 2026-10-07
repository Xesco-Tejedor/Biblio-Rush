# Biblio Rush

Juego de plataformas y velocidad ambientado en una biblioteca. Corre, salta y rueda para recoger libros, esquivar obstáculos y llegar a la salida. Incluye gráficos dibujados en Canvas y música y efectos sintetizados en el navegador.

[Abrir el juego](https://xesco-tejedor.github.io/Biblio-Rush/) · [Repositorio](https://github.com/Xesco-Tejedor/Biblio-Rush)

## Objetivo y niveles

Recorre tres niveles: **Sala de lectura**, **Archivo viejo** y **Hemeroteca nocturna**. Recoge libros, aprovecha los impulsos y evita los fosos, el polvo y las multas. Los puntos de control aparecen como sellos.

Empiezas con tres vidas. Al llegar a la salida se muestra el resultado del nivel y puedes continuar al siguiente. El juego conserva un récord local de libros, no una clasificación online.

## Cómo empezar

1. Abre el juego en un navegador moderno.
2. Toca la pantalla o pulsa **Enter**. Si el sonido aún no está activo, la primera interacción lo activa; vuelve a tocar o pulsar Enter para empezar.
3. Avanza recogiendo libros. Salta los huecos y rueda para atacar enemigos.
4. Tras completar un nivel, toca o pulsa Enter cuando aparezca la opción de continuar.
5. Al terminar la partida, vuelve a la pantalla inicial para jugar otra vez.

## Controles de teclado

| Acción | Teclas |
| --- | --- |
| Moverse a la izquierda | Flecha izquierda o A |
| Moverse a la derecha | Flecha derecha o D |
| Saltar | Espacio, flecha arriba, W o Z |
| Rodar | Flecha abajo, S, X o Shift |
| Pausar o reanudar | P o Escape |
| Empezar o avanzar entre pantallas | Enter |

## Controles táctiles y sonido

En dispositivos con puntero táctil aparecen botones para moverse, saltar y rodar. Mantén pulsada la dirección para correr. Tocar la pantalla también permite empezar y avanzar entre las pantallas de la partida.

El botón de sonido de la esquina superior derecha activa o silencia la música y los efectos. Los navegadores requieren una interacción antes de reproducir audio.

Si la ventana pierde el foco, la partida se pausa automáticamente. Pulsa P, Escape o toca el área del juego para reanudarla.

## Datos guardados y límites

Se conservan el récord y la preferencia de sonido mediante almacenamiento local. No se guarda una partida en curso ni hay sincronización entre dispositivos. Si borras los datos del sitio o cambias de navegador, el récord puede perderse.

El juego está implementado en una sola página, sin llamadas a servicios de IA ni registro de usuario. Su rendimiento y el audio dependen del dispositivo y del navegador. Los controles táctiles están implementados, pero eso no garantiza una experiencia idéntica en todos los móviles.

## Ejecutarlo en local

El código, los gráficos y la síntesis de sonido están en `index.html`. No hay un paso de compilación ni paquetes que instalar. Puedes abrir el archivo en el navegador o servir una copia con Python 3:

```bash
git clone https://github.com/Xesco-Tejedor/Biblio-Rush.git
cd Biblio-Rush
python3 -m http.server 8000
```

Abre `http://localhost:8000`. El juego no necesita los servicios externos de las otras aplicaciones del autor.
