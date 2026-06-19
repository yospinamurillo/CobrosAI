# CobrosAI

**CobrosAI** es una maqueta estática de la página de aterrizaje (landing page) para un producto que automatiza y mejora la gestión de cobros usando inteligencia artificial. El proyecto contiene HTML y estilos CSS embebidos que muestran el diseño y la propuesta de valor de la plataforma.

## Vista previa / Demo

- Archivo principal: `cobrosai-landing.html`
- Para ver la landing localmente, abre `cobrosai-landing.html` en tu navegador o ejecuta un servidor estático desde la carpeta del repositorio. Por ejemplo:

  ```bash
  # con Python 3
  python -m http.server 8000
  # luego abre http://localhost:8000/cobrosai-landing.html
  ```

## Qué incluye este repositorio

- `cobrosai-landing.html` — HTML completo con estilos en el head que implementa la landing page (secciones: hero, preview del dashboard, features, precios, testimonios y CTA).

El repositorio actualmente es una maqueta (prototipo estático) pensada para mostrar diseño y contenido; no incluye back-end ni integración con APIs de mensajería o pasarelas de pago.

## Estructura propuesta

Si decides evolucionar el proyecto a una aplicación real, una estructura recomendable podría ser:

- /public — archivos estáticos (HTML, CSS, imágenes)
- /src — código fuente (React/Vue/Svelte u otro framework)
- /server — backend (APIs, autenticación, envíos de mensajes)
- /docs — documentación adicional

## Contribuir

Si quieres ayudar a mejorar el diseño o el contenido:

1. Haz fork del repositorio.
2. Crea una rama con tu cambio: `git checkout -b feat/nombre-cambio`.
3. Haz commits claros y descriptivos.
4. Abre un Pull Request desde tu fork hacia este repositorio.

Para cambios rápidos en contenido o correcciones de texto puedes abrir un issue describiendo lo que quieres cambiar.

## Desarrollo local

Recomendaciones básicas para trabajar con la maqueta:

- Usa un servidor local para probar rutas y recursos (ver comando de Python arriba).
- Para editar estilos, modifica el bloque `<style>` dentro de `cobrosai-landing.html` o extrae el CSS a un archivo separado `styles.css` en `/public`.
- Si quieres añadir imágenes, crea una carpeta `public/images` y enlaza las rutas relativas desde el HTML.

## Contacto

Para demo o consultas de producto aparece en la landing el correo: `hola@cobrosai.co`.

## Licencia

La licencia no está definida en este repositorio. Si quieres publicar este proyecto con una licencia, añade un archivo `LICENSE`. Una opción habitual es la licencia MIT.

---

_Archivo generado automáticamente del contenido actual del repositorio._
