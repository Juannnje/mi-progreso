MI PROGRESO - aplicación web instalable (PWA)

CONTENIDO
- index.html: interfaz
- app.js: lógica y almacenamiento local
- manifest.webmanifest: configuración PWA
- sw.js: caché para uso offline después de la primera visita
- icons/: iconos

PUBLICAR GRATIS CON GITHUB PAGES
1. Descomprime este ZIP.
2. Crea un repositorio nuevo en GitHub.
3. Sube TODOS los archivos y la carpeta icons (index.html debe quedar en la raíz).
4. En Settings > Pages, elige Deploy from a branch, branch main y folder /(root), y guarda.
5. Espera la URL publicada.
6. En tu iPhone abre esa URL con Safari > Compartir > Añadir a pantalla de inicio.

IMPORTANTE
- El almacenamiento usa localStorage del navegador en ese dispositivo. No sincroniza entre dispositivos.
- Exporta periódicamente el respaldo JSON desde Historial.
- Para que la instalación PWA y el modo offline funcionen, publica en HTTPS. El service worker requiere HTTPS (o localhost).
- Esta app es un organizador personal, no sustituye evaluación médica ni calcula automáticamente nutrientes de alimentos.
