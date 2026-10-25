# La Barra Negra

Sitio web de La Barra Negra, beer wall self-service móvil en Querétaro.

- `index.html`: sitio completo (HTML, CSS y JS en un solo archivo, sin build).
- `logo.jpg`: logo.
- `img/`: primeras piezas para redes sociales.
- `social/`: kit de lanzamiento para redes (39 imágenes) y `social/ESTRATEGIA.md` con la estrategia por red.
- `og.jpg`: imagen de vista previa al compartir el link.

## Configuración

Pon el número de WhatsApp del negocio en `index.html`, en la línea `const WA_NUMBER = "";` (formato `524421234567`).

## Deploy en Vercel

Importa este repositorio en Vercel con Framework Preset **Other**, sin build command y con output directory vacío. Cada push a `main` publica una nueva versión.
