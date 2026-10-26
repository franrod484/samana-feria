# Samaná | Página web lista para GitHub Pages

## Cómo publicarla

1. En https://github.com/new crea un repositorio público llamado `samana-feria`.
2. En el repositorio, haz clic en «Add file» > «Upload files» y sube únicamente `index.html` (puede estar acompañado de este README).
3. Confirma con «Commit changes».
4. En «Settings» > «Pages», selecciona «Deploy from a branch», rama `main`, carpeta `/(root)` y guarda.
5. Una vez desplegado, visita: `https://TU-USUARIO.github.io/samana-feria/`.
6. Para tu dominio de GoDaddy, en «Settings» > «Pages» > «Custom domain» introduce `samana.tudominio.com` si prefieres conservar la web principal de tu dominio.
7. En el DNS de GoDaddy crea un registro CNAME: host `samana` -> valor `TU-USUARIO.github.io` (sin `https://` ni el nombre del repositorio). No toques los registros MX de correo.
8. Cuando GitHub termine de validar DNS, activa «Enforce HTTPS».

Si este dominio entero es SOLO para Samaná, en lugar de subdominio puedes usar el dominio raíz; lee https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site para configurar sus registros A.

La imagen principal es una ilustración digital, no una fotografía documental.
El archivo index.html incluye el CSS, JavaScript y la ilustración embebidos: no necesita carpeta de imágenes.
