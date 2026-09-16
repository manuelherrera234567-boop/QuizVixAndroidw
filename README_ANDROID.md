# QuizVix — Android

Este proyecto convierte el prototipo web de QuizVix en una app Android instalable.

## Compilar desde el teléfono con GitHub

1. Descarga este ZIP.
2. En GitHub crea un repositorio nuevo, por ejemplo `QuizVixAndroid`.
3. Sube el contenido de esta carpeta al repositorio (no el ZIP dentro del repositorio).
4. Entra a **Actions**.
5. Abre **Build QuizVix APK**.
6. Pulsa **Run workflow**.
7. Cuando termine, abre la ejecución y busca **Artifacts**.
8. Descarga `QuizVix-debug-apk`.
9. Extrae ese ZIP y abre `app-debug.apk` para instalarlo.

Esta APK es de prueba/debug. Después podemos preparar una versión release firmada para publicación.

## Estado actual

- 10 preguntas por ronda.
- Categorías del prototipo.
- XP, niveles, racha y desafío diario.
- Datos locales con localStorage.
- Sin ranking online todavía.
- Sin AdMob todavía.
