# Metafísica Party Bienio Filosófico UCB 🎮

Juego educativo de tablero para 1–4 equipos, con Hume, Kant y Hegel. Incluye siete minijuegos, dados virtuales, sistema de estrellas y puntuación, guardado local y **soporte para mandos USB / 2.4 GHz** mediante la Gamepad API.

## Cómo jugar con mando (TGZ-706W y otros)

1. Conecta el receptor USB de tu mando a la computadora y enciende el control.
2. Abre el juego en Chrome o Edge y pulsa un botón del mando.
3. Usa la **palanca izquierda** o **cruceta** para recorrer los botones y respuestas.
4. Pulsa **A** (habitualmente botón 0) para seleccionar, lanzar el dado o continuar.
5. Si el botón A no responde, pulsa el icono de engranaje ⚙, elige **Asignar** y después pulsa el botón físico que quieras.
6. Puedes conservar el ratón y teclado; no es necesario instalar un emulador.

Los mandos genéricos pueden presentar un orden de botones diferente: usa la configuración en pantalla. El navegador necesita recibir primero una pulsación para detectar el mando. El control debe estar reconocido por Windows (puedes comprobarlo con `joy.cpl`).

## Publicación en GitHub Pages

1. Crea un repositorio público nuevo en GitHub, por ejemplo `metafisica-party-ucb`.
2. Sube **todos los archivos y la carpeta `guias`** que aparecen dentro de este ZIP, de modo que `index.html` quede en la raíz del repositorio.
3. Pulsa **Commit changes**.
4. En el repositorio entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**, `main` y `/(root)`, y guarda.
6. GitHub mostrará la URL pública de tu juego cuando termine el despliegue. Prueba desde esa URL y recarga si el navegador conserva una versión en caché.

No necesita servidor, base de datos, dependencias, compilación, inicio de sesión ni conexión con ChatGPT para ejecutarse. El progreso se guarda localmente en el navegador mediante `localStorage`.

## Archivos

- `index.html`: página principal.
- `style.css`: diseño del tablero, minijuegos y pantallas.
- `data.js`: preguntas, casos y contenido filosófico de los siete minijuegos.
- `app.js`: lógica original del juego con soporte adicional para mando.
- `icon.svg`: favicon.
- `guias/estudiantes.html`: guía de juego.
- `guias/profesora.html`: guía docente.

**Nota:** La versión publicada previamente en `chatgpt.site` es independiente; subir esta carpeta a GitHub Pages crea/actualiza el sitio de GitHub y no modifica el otro enlace.
