# Web portfolio de Miguel Ebana

Sitio estático en un solo archivo: `index.html` (HTML, CSS y JS). Se puede abrir directamente en el navegador o subir tal cual a Netlify, GitHub Pages, Vercel o cualquier hosting.

## Añadir los vídeos
1. Sube cada vídeo a YouTube o Vimeo (puede ser "oculto"/"no listado").
2. Abre `index.html` y busca `const WORKS = [`.
3. En cada trabajo, pega la URL en `video: ""`, por ejemplo `video: "https://vimeo.com/123456789"`.
4. Cambia también `title`, `summary`, `text`, `duration` (timecode) y `note` según corresponda.

Para añadir un trabajo, copia un bloque `{ ... }` entero y cambia su `id` (sin espacios). La categoría (`cat`) crea su filtro automáticamente.

Con un vídeo de YouTube la miniatura sale sola. Para Vimeo puedes añadir `thumb: "ruta/imagen.jpg"`; si no, se dibuja una forma de onda.

## Créditos
La tabla sale de `const CREDITS = [` (datos del CV).

Cada trabajo tiene enlace directo: `tuweb.com/#samsung`, `#fauna`, etc.
