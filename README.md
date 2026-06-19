# CobrosAI

**CobrosAI** es una maqueta estática de la página de aterrizaje (landing page) para un producto que automatiza y mejora la gestión de cobros usando inteligencia artificial.

Visita el archivo principal: `cobrosai-landing.html` para ver el diseño.

Demo local

Para ver la landing localmente:

```bash
# desde la carpeta del repo
python -m http.server 8000
# abre http://localhost:8000/cobrosai-landing.html
```

GitHub Pages

Si quieres publicar la landing como sitio estático en GitHub Pages puedes hacerlo de dos maneras:

- Opción rápida: añade `index.html` en la raíz (ya incluido) y activa Pages en Settings → Pages → Source: branch `main` / root.
- Alternativa (recomendado): mueve los archivos a la carpeta `/docs` y selecciona `main / docs` como fuente en Pages.

Capturas (placeholder)

![Preview](./screenshots/preview.svg)

Contenido del repositorio

- `cobrosai-landing.html` — HTML con la landing.
- `styles.css` — CSS extraído desde el HTML para facilitar edición.
- `README.md` — este archivo (ES / EN).
- `LICENSE` — licencia MIT.
- `CONTRIBUTING.md` — guía para contribuir.
- `screenshots/preview.svg` — placeholder de captura de pantalla.

Cómo contribuir

1. Haz fork del repositorio.
2. Crea una rama nueva: `git checkout -b feat/nombre-cambio`.
3. Haz tus cambios y commitea con mensajes claros.
4. Abre un Pull Request describiendo los cambios.

Si planeas cambios técnicos (API, integraciones), abre antes un issue para discutir el diseño.

Licencia

Este proyecto se publica bajo la licencia MIT. Consulta el archivo `LICENSE`.

Contacto

Para consultas o demo: `hola@cobrosai.co`

---

EN — English version

# CobrosAI

CobrosAI is a static landing page mockup for a product that automates invoice collection using AI. This repository contains the HTML and CSS for the landing page and simple workflow notes to help you get started.

Preview

Open `cobrosai-landing.html` in your browser or run a local static server (see commands above).

GitHub Pages

To publish the site via GitHub Pages, place files in `/docs` or keep `index.html` at repository root and enable Pages in repository Settings.

Contributing

Please use forks and pull requests. For large changes, open an issue first.

License

MIT — see `LICENSE` for full text.
