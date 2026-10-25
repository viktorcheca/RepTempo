# RepTempo

Entrenador acústico gratuito para ejercicios de series y repeticiones. Funciona como web estática en GitHub Pages, sin servidor ni dependencias.


## Uso

Configura series, repeticiones, segundos para apretar y aflojar, pausas, descanso y volumen. Pulsa Empezar para activar el audio (el navegador exige una interacción). Usa Pausar/Reanudar y Detener cuando lo necesites.

El sonido ascendente indica contracción; el descendente, relajación; tres pitidos indican el fin de cada serie. Los valores quedan guardados en el dispositivo con localStorage.

## Nota móvil

Mantén la pestaña visible y el teléfono desbloqueado durante el ejercicio. Algunos navegadores suspenden el audio en segundo plano. Si cambias de aplicación o bloqueas la pantalla, RepTempo pausa automáticamente al detectar que la página queda oculta.

La duración estimada incluye la cuenta atrás y pausas entre repeticiones, pero no los tres pitidos finales (0,75 segundos por serie).
