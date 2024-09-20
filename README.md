# TP4 de Programación de Video Juegos 2: Controlador de Personaje en 3D

## Metodología

|                        |                                   |
| ---------------------- | --------------------------------- |
| Integrantes por grupo: | 1                                 |
| Se aprueba con         | 6                                 |
| Fecha de entrega       | Jueves 12 de Septiembre, 23:59 hs |
| Fecha de re-entrega    | Jueves 19 de Septiembre, 23:59 hs |
| Fecha de re-re-entrega    | Jueves 26 de Septiembre, 23:59 hs |


### Objetivos

- Aprender a implementar un personaje que se mueva en un entorno 3D
- Aprender a ponerse objetivos realistas que puedan cumplir en un cuatrimestre!

Recuerden que, por lo general, la solución más simple es la mejor.

---

## Comentarios para este cuatrimestre

### Código

- Ya no le voy a dar tanta importancia a cada línea de código que programaron. Para eso tuvimos el primer cuatrimestre.
- En cambio, ahora van a aplicar lo que aprendieron en un ejemplo de la vida real. Van a resolver los problemas con lo que ya saben.
- No me interesa mucho la forma en la que lleguen a las soluciones. Pero tengan una mínima justificación para cuando les pregunte por que hicieron algo de una manera y no de otra.
- Si no mantienen un mínimo orden de su código o no respetan las normas de performance que les enseñe, podrían sufrirlo hacia el final del proyecto! No creo que hayan muchos problemas de este estilo, pero ténganlo presente.

### Assets

- Mi idea es que no compren ningún asset.
- Podrían comprar assets de sistemas de FPS, inventario, enemigos, etc. que les resuelva mucho de los TPs que van a hacer. Pero no se los recomiendo porque:
	- No aprenderían mucho de lo que vamos a ver
	- Gastarían plata en algo que aun no saben si van a seguir usando
	- Tendrían que invertir tiempo aprendiendo un nuevo sistema. Y capaz les termine llevando mas tiempo porque los sistemas que vamos a implementar son sencillos.
- Si igual quieren comprar alguno, sería mejor que vayan por las cosas que no vamos a ver en la materia. O sea, contenido: modelos, texturas, sonidos, etc.

### Idea del juego

En base a sus votos, elegí un juego con éstas características:

- FPS (con disparos de armas de fuego o algún tipo de proyectil)
- Terror de Supervivencia
- Sigilo + Acción
- Equipamiento
- Quests (si llegamos con el tiempo)

Por lo que durante el cuatrimestre me van a ver hacer un juego con una mezcla de:

- Dishonored / DeusEx
- Resident Evil / Silent Hill

Les recomiendo que el juego que elijan se mantenga en esos márgenes, asi pueden aprovechar las clases para implementar sus mecanicas. No creo que sea problemático porque todas sus ideas tienen esos elementos, algunos yéndose mas para el lado de disparos y otros para el terror.

Si así y todo quieren implementar un RimWorld con elementos de MOBA (?) pueden hacerlo. Pero van a tener que hacerse cargo de sus elecciones! Recuerden que ahora son ustedes los que se están agregando o sacando requerimientos del enunciado. Sean vivos al respecto y no se la compliquen.

----

## Entrega

### Resumen

En este repo van a encontrar `TEMPLATE_RESUMEN.md` para que rellenen con sus datos y lo agreguen a su repositorio.

### Código

Todo lo van a resolver en un repositorio de GitHub. Tiene que haber una `tag` que se llame `tp4`. Ese commit es el que voy a corregir.

Antes de la fecha limite me tienen que mandar el link a la tag `tp4` por mail a <me@diegofreijo.com>.
 
### Defensa

Les voy a estar mandando horarios para que cada uno se conecte y tengamos la devolución por Google Meet.

----

## Personaje

Este TP va a marcar el inicio del juego con los controles básicos del personaje. El objetivo es que entreguen una escena de demostración (ahora no importa el nivel) donde se cumplan los siguientes requerimientos.

### Movimiento

Un personaje que se mueva por el mundo con WASD

### Disparos

- El jugador va a disparar algún proyectil:
	- balas con armas de fuego, arco y flecha, bolas de fuego, hechizos de parálisis, misiles nucleares, etc
- Probablemente los proyectiles se agoten de alguna manera y haga falta recargarlos. Por ejemplo:
	- Recargando el arma con balas del nivel
	- Esperando que se recargue una barra de mana
	- Esperando que se enfríe el arma

### Pickup

Que haya algún elemento que se pueda levantar de la escena. Por ej:
- Municiones para el arma
- Pociones de mana o salud
- Un ítem para avanzar en el juego (no hace falta que el ítem haga algo por ahora, solo poder levantarlo)
- Equipamiento (si es que hay)

### Equipamiento (opcional)

Si quieren agregar equipamiento al juego, siéntanse libres de hacerlo. Pero no quiero darle tanta importancia porque puede hacerse muy complejo muy rápido. Les recomiendo que agreguen un sistema de equipamiento si:

- No tienen otra cosa para hacer pickup, como balas o llaves para abrir puertas en un futuro.
- El equipamiento esta muy ligado con la forma en que su personaje dispara o se mueve por el mundo. Por ej, si esa capa de invisibilidad es indispensable para poder pasar sigilosamente por al lado de todos los amigos de Cthulhu.
- Solo van a agregar un equipamiento sencillo: por ejemplo, agarrar chalecos de kevlar que se va desgastando a medida que te disparan como en Counter Strike. Ahí el equipamiento en realidad seria como una segunda salud que se va bajando, así que es dentro de todo fácil de hacer.


