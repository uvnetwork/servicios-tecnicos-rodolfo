# Servicios Técnicos Rodolfo — Web estática

Página web estática (one-page) para **Rodolfo Peña - Servicios Técnicos**,
equipo de servicios técnicos en Alcorcón y zona sur de Madrid.

## Stack

- HTML5 semántico + Tailwind CSS (CDN)
- Iconos Lucide
- Sin backend: el formulario envía la solicitud como mensaje de WhatsApp
  (para email, ver nota sobre Formspree en el código)

## Publicación

- **GitHub Pages** en la rama `main` (raíz del repo)
- **Dominio personalizado:** `rodolfo.uvnet.es` (archivo `CNAME`)
- Requiere en el DNS de IONOS: registro `CNAME` de `rodolfo` → `uvnetwork.github.io`

## Editar

Todo el contenido está en `index.html` (comentarios en español).
Para previsualizar localmente, basta abrir el archivo en el navegador
o servir la carpeta con `python -m http.server` / Live Server.
