# Potenciando tus redes sociales — Agencia creativa de marketing digital

Sitio estático (un solo `index.html`) para publicar en GitHub Pages con el dominio **potenciandoredes.com**.

## Archivos
- `index.html`: el sitio completo (logo, estilos y formulario incluidos).
- `og-image.png`: imagen que se muestra al compartir el link en WhatsApp, LinkedIn y redes.
- `CNAME`: indica el dominio personalizado. No lo borres.
- `.nojekyll`: evita que GitHub procese el sitio con Jekyll.
- `robots.txt` y `sitemap.xml`: ayudan a que Google encuentre el sitio.

## Pasos para publicarlo
1. Crear un repositorio público en GitHub (por ejemplo `potenciandoredes`) y subir estos archivos a la raíz.
2. Settings > Pages > Deploy from a branch > rama `main` y carpeta `/ (root)`.
3. En "Custom domain" escribir `potenciandoredes.com` y guardar.
4. En el panel del dominio, cargar 4 registros A en `@` (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153), 4 AAAA en `@` (2606:50c0:8000::153, 2606:50c0:8001::153, 2606:50c0:8002::153, 2606:50c0:8003::153) y un CNAME `www` hacia `TU-USUARIO.github.io`.
5. No borrar los registros MX ni TXT (son los del correo).
6. Cuando GitHub confirme el dominio, tildar "Enforce HTTPS".
