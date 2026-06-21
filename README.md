# Latino TV — Actualizaciones

Canal de actualizaciones de la app **Latino TV** (Android TV / TV Box).

Aquí solo se publica el **APK** ya compilado y el archivo `version.json` que la app
lee para avisar a los clientes cuando hay una versión nueva. **El código fuente NO
está aquí** (es privado).

## Cómo publicar una nueva versión
1. Subir el `versionCode` en `app/build.gradle.kts` y compilar el APK nuevo.
2. Crear un *Release* nuevo (ej. `v1.2`) y subir el `IPTV.apk`.
3. Editar `version.json` con el nuevo `versionCode`, `versionName` y el enlace al APK.

La app revisa `version.json` al abrir y, si hay una versión mayor, ofrece actualizar.
