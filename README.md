# RepTempo

Entrenador acústico gratuito para ejercicios de series y repeticiones. Funciona como web estática en GitHub Pages, sin servidor ni dependencias.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `reptempo`.
2. Sube `index.html`, `style.css` y `app.js` a la **raíz** del repositorio (no dentro de una carpeta).
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main`, carpeta `/(root)` y guarda.
5. La URL habitual será `https://TU-USUARIO.github.io/reptempo/` una vez publicado.

## Uso

Configura series, repeticiones, segundos para apretar y aflojar, pausas, descanso y volumen. Pulsa Empezar para activar el audio (el navegador exige una interacción). Usa Pausar/Reanudar y Detener cuando lo necesites.

El sonido ascendente indica contracción; el descendente, relajación; tres pitidos indican el fin de cada serie. Los valores quedan guardados en el dispositivo con localStorage.

## Nota móvil

Mantén la pestaña visible y el teléfono desbloqueado durante el ejercicio. Algunos navegadores suspenden el audio en segundo plano. Si cambias de aplicación o bloqueas la pantalla, RepTempo pausa automáticamente al detectar que la página queda oculta.

La duración estimada incluye la cuenta atrás y pausas entre repeticiones, pero no los tres pitidos finales (0,75 segundos por serie).
