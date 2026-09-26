TC Max — PWA lista para publicar
================================

Archivos principales:
- index.html: aplicación y almacenamiento local.
- manifest.webmanifest: metadatos de instalación PWA.
- sw.js: funcionamiento offline y caché de la aplicación.
- icon-192.png / icon-512.png: iconos Android/PWA.
- vercel.json: cabeceras recomendadas para despliegue en Vercel.

DATOS
- El historial se guarda en localStorage: no se envía a ningún servidor.
- El almacenamiento pertenece al origen HTTPS donde se publique la app.
- Se incluye Exportar copia e Importar copia para migrar/restaurar datos.

INSTALACIÓN EN ANDROID
1. Publicar estos archivos en una URL HTTPS.
2. Abrir la URL con Chrome en Android.
3. Tras cumplir las condiciones de instalación de Chrome, aparecerá el botón “Instalar aplicación”; también puede usarse el menú de Chrome > Instalar aplicación / Añadir a pantalla de inicio.
4. Tras la primera carga, la app queda preparada para funcionar offline.
