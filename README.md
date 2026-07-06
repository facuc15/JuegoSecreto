# 🎲 Juego del Número Secreto

Juego web simple hecho en **HTML, CSS y JavaScript puro (vanilla)**, donde el usuario debe adivinar un número secreto generado aleatoriamente entre 1 y 10.

## 📋 Descripción

Al cargar la página, el juego genera un número secreto aleatorio y le pide al usuario que lo adivine. Por cada intento fallido, el juego indica si el número secreto es **mayor** o **menor** al ingresado, hasta que el usuario acierte. Al finalizar, se muestra la cantidad de intentos realizados y se habilita la opción de iniciar una nueva partida.

## ✨ Características

- Generación de números aleatorios sin repetición dentro de una misma sesión de juego.
- Feedback dinámico ("el número es mayor" / "es menor") en cada intento.
- Contador de intentos.
- Botón para reiniciar el juego una vez adivinado el número.
- Interfaz visual con estilo tipo "consola/tech", tipografías personalizadas (Chakra Petch e Inter) e imágenes de fondo.

## 🗂️ Estructura del proyecto

```
JuegoSecreto-main/
├── index.html      # Estructura de la página
├── style.css       # Estilos visuales
├── app.js          # Lógica del juego
└── img/
    ├── bg.png
    ├── code.png
    ├── ia.png
    └── Ruido.png
```

## 🚀 Cómo ejecutarlo

No requiere instalación ni dependencias. Solo hay que:

1. Descargar o clonar el repositorio.
2. Abrir el archivo `index.html` en cualquier navegador web.

## 🕹️ Cómo se juega

1. Ingresá un número entre 1 y 10 en el campo de texto.
2. Presioná el botón **"Intentar"**.
3. El juego te indicará si el número secreto es mayor o menor al que ingresaste.
4. Repetí hasta acertar.
5. Al acertar, se mostrará cuántos intentos te tomó y se habilitará el botón **"Nuevo juego"** para volver a jugar.

## 🛠️ Tecnologías utilizadas

- **HTML5**
- **CSS3** (Flexbox, gradientes, tipografías de Google Fonts)
- **JavaScript** (DOM, manipulación de eventos, `Math.random()`)

## 📌 Detalles técnicos

- `generarNumeroSecreto()`: genera un número aleatorio del 1 al 10 evitando repetir números ya sorteados en la misma sesión, guardándolos en `listaNumerosSorteados`.
- `verificarIntento()`: compara el número ingresado con el número secreto y actualiza el mensaje en pantalla.
- `reiniciarJuego()`: reinicia las condiciones del juego y deshabilita nuevamente el botón de reinicio.

## 📄 Licencia

Este proyecto es de uso libre con fines educativos.
