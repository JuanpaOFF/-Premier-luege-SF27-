# Premier Luege SF27 — FULL

Incluye menú retro-moderno, fondo degradado morado/azul/verde, animaciones, clubes y logos suministrados, competiciones, cartas base, chat con usuario persistente local, vídeos y Admin Editor.

## GitHub Pages
GitHub Pages sirve el frontend, pero no ejecuta Node. Por eso el buscador de vídeos funciona como búsqueda oficial de YouTube cuando el backend no está conectado.

## YouTube integrado
Para búsqueda real dentro de la web: ejecuta `npm install` y `npm start` en un servidor Node, configurando `YOUTUBE_API_KEY` y `ADMIN_PASSWORD`. Nunca pongas la API key en `app.js`.

## Chat y Admin
El chat de esta versión es local al navegador. Para que todos los miembros vean los mismos mensajes hay que añadir una base de datos/WebSocket. El Admin Editor es la interfaz inicial y el servidor tiene una ruta protegida de prueba.

## GitHub
Sube el contenido del proyecto. `index.html` debe quedar en la raíz de la fuente publicada.
