# Portfolio

Publicado en https://brianclaros.github.io/ (repo `BrianClaros.github.io`, GitHub Pages desde `main`). Hasta noviembre de 2026 estuvo en `brianclaros.github.io/portfolio/`; esa URL ya no existe.

## Estructura

- `index.html`: landing completa (markup, estilos y script inline: traducción ES/EN vía atributos `data-en`, tema claro/oscuro, menú mobile y animaciones de scroll).
- `assets/img/`: foto de perfil optimizada (`brian.webp`) e imagen para Open Graph (`brian-og.jpg`).
- `assets/favicon.svg`: favicon del sitio.
- `cv.md` / `cv_en.md`: CV fuente en español e inglés.
- `CV_Brian.pdf` / `CV_Brian_en.pdf`: CVs descargables desde el botón del header (según el idioma activo) y enlazados desde devecoop.com.ar (`https://brianclaros.github.io/CV_Brian.pdf`).
- `cv.css` + `build-cv.sh`: estilos y script para regenerar los PDFs (`./build-cv.sh`, requiere pandoc y Chrome).
- `photo.png`: foto de perfil cuadrada (84×84) servida para usarse desde otros sitios, p. ej. devecoop.com.ar/socies.html vía `https://brianclaros.github.io/photo.png` (no la usa `index.html`; no borrar ni renombrar).
