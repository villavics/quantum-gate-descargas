# Quantum Gate

Videojuego educativo sobre compuertas cuánticas y la esfera de Bloch.

## Jugar en el navegador

**[Jugar Quantum Gate](https://villavics.github.io/quantum-gate-descargas/)**

Abre el enlace en una computadora, espera la carga y pulsa **Jugar**. No necesitas cuenta de GitHub ni instalar Godot. Usa teclado y ratón o mando; la interfaz está diseñada para computadora. La primera carga descarga aproximadamente 190 MB antes de la compresión del servidor y puede tardar según tu conexión.

La versión web del 20 de octubre de 2026 incluye los niveles 0→1→2, retos variables, Demo, ayudas, voces, música y el botón rojo **SALIR**. Conserva la corrección del audio entrecortado mediante mezcla con hilos. Necesita un navegador actualizado con WebGL 2, WebAssembly, SharedArrayBuffer y almacenamiento permitido; verificada en Chromium sobre Mac. El rendimiento puede variar según el equipo y el navegador.

Usa **SALIR → Guardar y cerrar** antes de cerrar la pestaña. Tu avance y los puntajes quedan en ese navegador y esa dirección; no se transfieren entre equipos ni desde la app de Mac. En una pestaña normal, el juego apaga el audio y muestra **Juego cerrado** para que puedas cerrarla.

[ZIP para servir localmente e instrucciones](https://github.com/villavics/quantum-gate-descargas/releases/tag/web-2026.10.20-r3). La primera visita prepara automáticamente el navegador y recarga una vez para habilitar el audio con hilos.

Si ya descargaste el ZIP y tienes Python 3 instalado, añade [los lanzadores automáticos (3 KB)](https://github.com/villavics/quantum-gate-descargas/releases/download/web-2026.10.20-r3/Lanzadores_Quantum_Gate.zip) junto a `index.html`, sustituyendo `serve.py`. Después abre **Jugar en Windows.bat**, **Jugar en Mac.command** o ejecuta **Jugar en Linux.sh** como programa. El servidor y el navegador se abren automáticamente; mantén la ventana del lanzador abierta mientras juegas.

## Descargar para Mac

**[Descargar Quantum Gate 1.31 para Mac con Apple Silicon](https://github.com/villavics/quantum-gate-descargas/releases/download/v1.31/Quantum_Gate_1.31_macOS_AppleSilicon.zip)** · aproximadamente 192 MB.

Compatible con M1, M2, M3, **M4** y posteriores; requiere macOS 13 o posterior. No necesitas cuenta de GitHub, Godot ni Blender. Después de descargarlo puedes jugar sin Internet.

1. Descomprime el ZIP.
2. Mueve **Quantum Gate.app** completa a Aplicaciones o a otra carpeta.
3. Abre la app y consulta **Ayuda** para empezar.

La app tiene firma local ad hoc y **no está notarizada por Apple**. Si macOS impide abrirla por desarrollador no verificado y confías en esta descarga, intenta abrirla y luego entra en **Ajustes del Sistema → Privacidad y seguridad → Abrir igualmente**. [Instrucciones de Apple](https://support.apple.com/es-mx/102445). No desactives Gatekeeper; si aparece un aviso de malware o archivo dañado, informa del mensaje exacto.

[Notas de la versión e integridad SHA-256](https://github.com/villavics/quantum-gate-descargas/releases/tag/v1.31). El ZIP incluye LEEME.txt con instrucciones.

## Qué incluye la versión 1.31

Retos variables, teclado virtual, Demo durante la partida, guardado y recuperación, trayectorias ideales por compuerta, tablero reorganizado y anuncios grabados de Orelia. **Y y S están retiradas del tablero y de los retos actuales**; permanecen X, H, Z, T y Rx/Ry/Rz según el nivel. Sin saludo hablado por nombre.

## Plataformas

| Plataforma | Versión | Estado |
| --- | --- | --- |
| macOS con Apple Silicon | 1.31 | Descarga pública disponible; verificada en Mac Apple Silicon |
| macOS Intel | — | Sin paquete compatible publicado |
| Linux x86_64 | 1.30 | Paquete preparado; prueba en Linux y publicación pública pendientes |
| Windows | — | Sin artefacto verificado |
| Navegador web | web-pages-r3 · 2026-10-20 | [Jugar desde GitHub Pages](https://villavics.github.io/quantum-gate-descargas/) |

El rendimiento y la salida de sonido del equipo receptor se comprueban allí; las pruebas realizadas no garantizan una tasa de fotogramas en cada modelo de Mac.

## Datos y créditos

En la app, las partidas y los puntajes se guardan en la cuenta local de quien juega, fuera de la aplicación. En la versión web se guardan en los datos locales del navegador para ese sitio. Los paquetes no incluyen contraseñas, partidas ni puntajes personales. Consulta Créditos dentro del juego y los avisos de licencia incluidos.

Este repositorio distribuye aplicaciones e instrucciones. No contiene el proyecto editable ni los respaldos privados de desarrollo.
