# Krahz Systems

Página índice de las webapps personales de Krahz (Noticiahz, Caravanahz, Mediaskinhz).
La web está en `site/` (un solo `index.html`, sin build) y se publica sola en Cloudflare Pages
al subir cambios a la rama `main` (ver `.github/workflows/deploy.yml`).

- Estilo: el de Noticiahz (paleta, Inter + Newsreader, tema claro/oscuro).
- Añadir un proyecto: copiar un bloque en `PROJECTS` dentro de `site/index.html` y poner su icono
  (192 px) en `site/ic/`. Los proyectos que aún están en local van comentados al final de la lista.
- Antes de publicar se comprueba que `index.html` existe y que todos los iconos que usa están en `site/ic/`.
