# Mi Rutina Diaria
App Android con horario semanal, actividad actual, siguiente actividad y recordatorios locales 10 minutos antes.

## Crear APK en GitHub
1. Crea repositorio nuevo.
2. Descomprime este ZIP y sube **todos sus archivos** a la raíz, incluida la carpeta oculta `.github`.
3. Abre Actions > Compilar APK > Run workflow, o espera la ejecución automática al subir a main.
4. Descarga el artifact MiRutinaDiaria-APK, descomprímelo e instala `app-debug.apk`.
5. Permite notificaciones y alarmas exactas en Android. El ahorro de batería puede retrasar avisos.

El horario se modifica en `app/src/main/assets/schedule.json`.
