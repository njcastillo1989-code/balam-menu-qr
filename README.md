# BALAM NIGHT CLUB — Menú QR bilingüe

## Archivos
- `index.html`: página principal.
- `styles.css`: diseño adaptable a celular.
- `app.js`: selector ES/EN, navegación y búsqueda.
- `menu-data.js`: productos y precios editables.
- `assets/balam-logo.jpeg`: logo proporcionado.

## Antes de publicar
1. Revisa `menu-data.js` y confirma los precios. Los importes de alimentos MXN se dejaron vacíos porque las imágenes compartidas solo mostraban precios en USD; no se inventaron conversiones.
2. En bebidas, las celdas sin precio USD se muestran como “Por confirmar / To be confirmed”.
3. Algunas cifras pequeñas deben verificarse contra los originales antes de publicar.

## Publicar gratis con GitHub Pages
1. Entra a https://github.com y crea una cuenta o inicia sesión.
2. Crea un repositorio público llamado `balam-menu-qr`.
3. Sube el contenido de esta carpeta (no la carpeta contenedora): `index.html`, `styles.css`, `app.js`, `menu-data.js` y la carpeta `assets`.
4. En el repositorio, abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio. La URL será similar a `https://TU-USUARIO.github.io/balam-menu-qr/` (sustituye TU-USUARIO por tu usuario real).
7. Abre el enlace desde un celular y prueba ES/EN, categorías y precios.

## Crear el QR definitivo
Después de confirmar que la web ya está pública, genera un QR estático con la URL real del sitio. No uses una URL inventada o temporal. Prueba el QR desde otro celular antes de imprimirlo. Si actualizas los productos pero mantienes la misma URL, el QR sigue siendo válido.

## Actualizar precios
Edita `menu-data.js` y vuelve a subir el archivo al repositorio. No cambies la dirección de la página si quieres conservar el mismo QR.

Nota: GitHub Pages publica el contenido de forma pública. No incluyas datos privados.
