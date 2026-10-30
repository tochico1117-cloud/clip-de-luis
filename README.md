# CLIP DE LUIS — proyecto inicial Android

Este paquete contiene un proyecto Android Studio inicial con una interfaz WebView local.

## Qué funciona en este prototipo
- Interfaz adaptable a móviles.
- Validación básica de enlaces HTTPS compatibles.
- Selector de modo (viral, historia, debate, humor), duración, subtítulos y formato.
- Flujo de demostración con tarjetas de momentos de ejemplo.

## Qué NO está implementado todavía
- No descarga, transcribe ni analiza el vídeo real.
- No genera/exporta clips MP4.
- Las puntuaciones y tarjetas son demostrativas.
- No incluye backend ni claves de IA.

Para analizar vídeos reales se debe añadir un backend autorizado para obtener/transcribir el contenido, un modelo de análisis y un motor de recorte/renderizado. Los enlaces de plataformas pueden estar sujetos a permisos, API, derechos de autor y restricciones técnicas.

## Cómo abrir y compilar
1. Instala Android Studio en un ordenador.
2. Abre la carpeta `ClipDeLuis` como proyecto.
3. Permite que Gradle sincronice y descargue el Android Gradle Plugin.
4. Ejecuta en un dispositivo/emulador o usa Build > Build APK(s).

Requisitos orientativos: Android Studio reciente, JDK 17 y Android SDK Platform 35.
