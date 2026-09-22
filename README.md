# Galaxia de flores amarillas

Adaptación editable de la página facilitada por el usuario:
https://cdn.dedicacodes.com/t/galaxia-nebulosa-flores-amarillas/1.0.0/index.html

Se conserva la animación original. El código se ha separado para facilitar la edición.

## Subir a GitHub

1. Crea un repositorio público llamado `flores-amarillas`.
2. Descomprime el ZIP en tu computadora.
3. En el repositorio, pulsa **Add file → Upload files** y arrastra todo el contenido de la carpeta descomprimida, incluida `assets`.
4. `index.html`, `config.js`, `galaxia.js` y `estilos.css` deben quedar en la raíz del repositorio, no dentro de otra carpeta. No subas solamente el ZIP.
5. Guarda con **Commit changes**.
6. Ve a **Settings → Pages**. En **Source**, elige **Deploy from a branch**, selecciona **main** y **/(root)** y pulsa **Save**.
7. Cuando termine de publicarse, GitHub mostrará el enlace. Normalmente será `https://TU-USUARIO.github.io/flores-amarillas/`.

## Personalizar

Abre `config.js` en GitHub, pulsa el lápiz para editar y guarda con **Commit changes**.

- `titulo`: el mensaje que aparece arriba.
- `frases`: las frases que flotan. Conserva las comillas y separa cada frase con una coma.
- `fotos`: rutas de imágenes. Puedes reemplazar `assets/img1.png`, `assets/img2.png` y `assets/img3.png` con tus imágenes o subir otras y cambiar las rutas. Cambiar una extensión de JPG a PNG no convierte la imagen: usa el nombre y extensión reales.
- `musica`: ruta del audio. Puedes reemplazar `assets/musica.mp3` con tu MP3.

Para cambiar colores y tamaños, edita `estilos.css`. Para cambiar la animación, edita `galaxia.js`.

La música empieza después de tocar «Toca para iniciar». Arrastra para girar; usa la rueda o pellizca con dos dedos para acercar y alejar.

## Requisitos

No necesita Node, PHP, instalación ni compilación. Usa Three.js y Google Fonts mediante Internet. Las fotos y el audio están incluidos localmente. Para probar los recursos antes de publicar, sirve la carpeta con `python -m http.server 8000` y abre http://localhost:8000. Evita abrir directamente con file:// porque el navegador puede restringir las texturas.

Procedencia: Dedicacodes; no se atribuye la autoría original ni se añade una licencia nueva a sus recursos.

Guía de GitHub Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
