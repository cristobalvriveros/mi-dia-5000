# Mi Día $5.000 — PWA

Aplicación web instalable para registrar gastos diarios. Presupuesto predeterminado: $5.000 CLP, reiniciado cada día. Permite asignar un presupuesto especial por fecha.

## Archivos
- `index.html`: aplicación completa.
- `manifest.webmanifest`: configuración de instalación.
- `sw.js`: caché para uso sin conexión después de la primera carga.
- `icon-192.png` y `icon-512.png`: iconos.

## Publicación necesaria
Para instalarla como PWA en Android, estos archivos deben estar publicados en un sitio HTTPS. Abrir `index.html` como archivo local no habilita la instalación PWA ni el service worker.

Una opción es subir los archivos a un repositorio y activar GitHub Pages desde el navegador del teléfono. Luego abrir la URL HTTPS en Chrome Android y elegir “Instalar aplicación” o “Añadir a pantalla de inicio”.

## Datos
Los registros se guardan en `localStorage` del navegador del dispositivo. Borrar los datos del sitio puede eliminarlos. Esta versión no sincroniza ni hace copias de seguridad en la nube.
