# Fake Shutdown Simulator v0.4

Incluye:
- `index.html`: simulación de escritorio y móvil.
- `favicon.svg`: icono del sitio.
- `og-banner.svg`: banner Open Graph/Twitter.
- `README.txt`: instrucciones de publicación.

## Móvil
- iPhone/iPad: interfaz de apagado inspirada en iOS y transición a pantalla negra tipo pantalla apagada.
- Android: interfaz propia y transición a reposo oscuro.
- La actividad táctil despierta la simulación.
- En Android y navegadores compatibles, el botón intenta activar Fullscreen.
- En iPhone, Safari no permite a una página web normal forzar fullscreen. La web explica cómo usar Compartir → Añadir a pantalla de inicio; el modo standalone depende de la versión de iOS y del navegador.

## Publicar
Sube los tres archivos a la misma carpeta pública.
Reemplaza `https://TU-DOMINIO.example/` en las etiquetas canonical, Open Graph y Twitter por el dominio real.
El banner SVG puede no ser aceptado por algunos crawlers sociales; si falla la previsualización, conviértelo a PNG 1200x630 y actualiza `og:image` y `twitter:image`.

La detección del sistema operativo es aproximada: los navegadores pueden ocultar o reducir la información de plataforma.
La simulación no apaga el dispositivo, no bloquea controles ni modifica el sistema.
