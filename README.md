# Violeta - Registro (app instalable)

## Sobre la privacidad
El código de la app no contiene ningún dato de Violeta — es solo la plantilla (botones, estilos, lógica). Los registros que guardes (tomas, pañales, sueño) quedan **solo en el navegador de tu celular** (almacenamiento local), nunca se suben a GitHub ni a ningún servidor. Publicar el repositorio como público es seguro para tus datos; solo hace público el código de la herramienta, no tu información.

Nota: GitHub Pages gratis requiere que el repositorio sea público. Si prefieres que el repositorio en sí sea privado, necesitas GitHub Pro (o una cuenta de organización con Pages en repos privados), o usar un servicio alterno como Netlify/Vercel en su capa gratuita (igual generan una URL pública, pero no aparece listada en ningún buscador ni la comparte GitHub).

## Pasos para publicarlo

1. Crea un repositorio nuevo en GitHub (por ejemplo `violeta-registro`). Público, para usar Pages gratis.
2. Sube estos archivos a la raíz del repo:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
3. Ve a **Settings → Pages** del repositorio.
4. En "Source" elige la rama `main` y la carpeta `/ (root)`. Guarda.
5. Espera 1-2 minutos. GitHub te dará una URL como:
   `https://tu-usuario.github.io/violeta-registro/`
6. Abre esa URL desde el navegador de tu celular (Chrome o Safari).
7. Toca el menú del navegador → **"Añadir a pantalla de inicio"** (Android) o **"Compartir" → "Añadir a pantalla de inicio"** (iPhone).
8. Ya queda como un ícono más en tu celular, abre a pantalla completa y funciona sin internet.

## Actualizaciones
Si luego quieres cambiar algo del diseño o la lógica, dime y te preparo los archivos actualizados para que los vuelvas a subir al mismo repo.
