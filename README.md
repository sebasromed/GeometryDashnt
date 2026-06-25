# Geometry Dash't

Una recreación lo más fiel posible de **Geometry Dash**, desarrollada desde cero en Unity.
Demostración en: https://youtu.be/7aGxON4VC30

## 📖 Descripción

El juego consiste en intentar hacer una recreación lo más fiel posible a Geometry Dash,
creando todos los modelos y texturas necesarios. Al usar modelos 3D —especialmente para
los bordes blancos de cada objeto— se ha jugado mucho con la perspectiva, y **todo ha sido
desarrollado teniendo en cuenta el ángulo de la cámara**.

## ✨ Características implementadas

- 🟦 **Dos modos de juego**: Cubo y Wave, conectados mediante portales.
- 🧲 **Mecánicas clásicas**: pads de salto, orbes, portales de gravedad y de modo.
- 🪙 **3 monedas secretas** por nivel.
- 🎨 **Triggers de color** que cambian el fondo y el suelo a lo largo del nivel.
- 🌀 **Fondo y suelo con scroll infinito**
- 💥 **Efecto de muerte**: el personaje se fragmenta en pedazos con explosión y sonido.
- ✨ **Efectos visuales**: rastro que deja el personaje, partículas de orbes y portales, animaciones de activación...
- 🏁 **Secuencia de meta** con cámara y trayectoria animadas.
- ⏸️ **Menú de pausa**, **menú principal** y **pantalla final** con intentos, saltos y monedas.

## 🎮 Controles

- **Espacio / Clic izquierdo** — saltar (cubo) / subir (wave).
- **Escape** — pausar.

## 🛠️ Aspectos técnicos

- **Física calibrada** para imitar la sensación del juego original lo máximo posible (velocidad, saltos, hitboxes...).
  Usar el grid de Unity ha sido de gran ayuda para que todo tenga distancias constantes y sea más fácil calibrar
- **Optimización por secciones**: solo se mantienen activas las secciones cercanas al jugador, así no está todo el nivel cargado en todo momento
  (con las animaciones, partículas, meshes, texturas, etc)

## 🎵 Recursos

Recursos creados específicamente para el proyecto: **todos los modelos 3D y texturas**.

Recursos extraídos del juego original: **efectos de sonido, canciones y sprites de la
interfaz** (botones, marcos, iconos...).

## 🧰 Hecho con

- **Unity 2023.2.22f1** · URP
- **Blender** (modelado y fracturado de los trozos)
- **GIMP** (texturas)
