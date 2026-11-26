MI PROGRESO 2.0 — EDICIÓN CON IDENTIDAD PERSONAL

Esta actualización incluye:
- Registro de alimentos por gramos y estimación de calorías, proteínas, carbohidratos y grasas.
- Resumen diario de macros y estadísticas de los últimos 7 días.
- Registro de entrenamientos, series, repeticiones y cargas.
- Gráficas de peso y cintura, historial y calendario.
- Recordatorios configurables (la página debe permanecer activa; no se garantiza entrega con la app cerrada).
- Nueva identidad visual basada en la ilustración elegida: iconos 192/512 y banner de bienvenida.
- Conserva la clave local miProgresoDataV1 para mantener los datos de la versión anterior.

ACTUALIZAR TU SITIO EN GITHUB PAGES
1. Antes de reemplazar nada, abre tu versión actual y ve a Historial > Exportar copia JSON.
2. Descomprime este ZIP.
3. En GitHub, abre el repositorio mi-progreso y reemplaza index.html, app.js, sw.js, manifest.webmanifest y README.txt.
4. En la carpeta icons, reemplaza icon-192.png e icon-512.png y agrega mi-progreso-brand.png. Conserva las rutas y nombres exactos.
5. Confirma los cambios con Commit changes. GitHub Pages publicará la actualización en la misma dirección.
6. En el iPhone, cierra y vuelve a abrir la app. Si aparece la versión anterior, abre el sitio en Safari y recarga. Puede ser necesario quitar el acceso anterior de la pantalla de inicio y volver a añadirlo para refrescar el icono.

IMPORTANTE
- Los registros se guardan en localStorage de ese navegador/dispositivo; no se sincronizan entre dispositivos.
- La clave de almacenamiento se mantiene para conservar registros anteriores. Haz igualmente una copia de seguridad antes de actualizar.
- Los nutrientes son estimaciones promedio y pueden variar por marca, corte y preparación.
- Los recordatorios requieren que la página permanezca activa; el navegador puede suspenderlos.
- La aplicación es una herramienta de seguimiento y no sustituye consejo médico o nutricional.
