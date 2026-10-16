# Una noche especial

Una experiencia romántica interactiva hecha con HTML, CSS y JavaScript.

## Verla en tu computadora
1. Descargá y descomprimí el ZIP.
2. Abrí `index.html` en tu navegador. Para una experiencia más fiel, usá la extensión **Live Server** de VS Code.

## Publicarla gratis en GitHub Pages
1. Creá un repositorio nuevo en GitHub.
2. Subí `index.html`, `style.css`, `script.js` y la carpeta `assets` completa.
3. En el repositorio, entrá a **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**.
5. Seleccioná `main` y `/ (root)`, y guardá.
6. GitHub te dará un enlace público cuando termine de publicar.

## Personalizar
- Se conservaron las 4 fotos originales (`assets/foto-01.jpg` a `assets/foto-04.jpg`) y se agregó `assets/foto-05.jpg`.
- El video nuevo está en `assets/recuerdo-video-01.mp4` y se reproduce desde el tablero.
- El tablero ya tiene 17 espacios en total: las 5 fotos, el video y 11 espacios vacíos para completar más adelante.
- La canción original se conserva en `assets/cancion.mp3`.

## Nota sobre el audio
Los navegadores suelen bloquear el sonido automático. La página intenta reproducir la canción al cargar; si el navegador lo impide, la interacción con la lámpara inicia la reproducción. El audio se mantiene durante las escenas.


## Ajustes de esta versión
- Música a volumen moderado (aprox. 22–28%) y entrada gradual al activarla.
- Tablero ampliado a 17 recuerdos, conservando las 4 fotos originales, y sumando una foto, un video y espacios vacíos para completar después.
- Fotos con más separación y sin recorte intencional (object-fit: contain).
- Diseño responsive: tablero amplio en escritorio y cuadrícula de dos columnas con desplazamiento vertical en móviles.
