# Servicios Técnicos Rodolfo — Notas del proyecto

## Flujo de trabajo Git

- Repo remoto: `https://github.com/uvnetwork/servicios-tecnicos-rodolfo` (público)
- Rama principal: `main`
- **Hacer `git pull` al inicio de cada sesión** para traer cambios remotos
- **Hacer `git push` automáticamente después de cada commit**
- **Todo cambio va en su propio commit documentado**: mensaje en español, formato Conventional Commits (`feat:`, `fix:`, `docs:`, `refactor:`, `chore:`) + cuerpo explicando el porqué del cambio

## Despliegue

- GitHub Pages: rama `main`, raíz — publica automáticamente cada push
- Dominio: `rodolfo.uvnet.es` (archivo `CNAME` + registro CNAME en IONOS → `uvnetwork.github.io`)
- Activar "Enforce HTTPS" en Settings > Pages una vez verificado el dominio
- `gh` CLI instalado en `"C:/Program Files/GitHub CLI/gh.exe"`

## Notas técnicas

- Sitio estático: un solo `index.html` — HTML5 semántico + Tailwind CDN + Lucide
- Comentarios del código en español
- Contacto real: `+34 622 70 62 88` y `+34 722 59 78 17` (ambos con WhatsApp), email `multiservicios.rodolfo@gmail.com`
- Formulario envía vía WhatsApp al primer número (622 70 62 88)
- Formulario sin backend: envía vía WhatsApp (Formspree documentado como alternativa)
- Imágenes: Unsplash con `onerror` fallback — si alguna falla, sustituir la URL
