# Quantum Gate

Videojuego educativo sobre compuertas cuánticas y la esfera de Bloch.

Este repositorio está preparado para alojar documentación de instalación y
versiones descargables mediante GitHub Releases. Aún no existe una publicación
pública asociada a esta preparación.

## Paquetes preparados

| Plataforma | Versión | Estado |
| --- | --- | --- |
| macOS con Apple Silicon | 1.30 | Paquete independiente existente; firma local ad hoc, sin notarización |
| Linux x86_64 | 1.30 | Paquete preparado; prueba en Linux pendiente |
| Windows | Pendiente | Sin artefacto verificado |
| Navegador web | Pendiente | Viabilidad y rendimiento por comprobar |

Los paquetes locales no son nuevos builds ni se publican automáticamente. Antes
de una Release se comprueban instalación, controles, imagen, sonido, guardado,
licencias y hashes en las plataformas correspondientes.

## Instalación

Mac: extraer el ZIP y conservar `Quantum Gate.app` completa. Su firma local no
equivale a Developer ID ni notarización de Apple.

Linux: extraer la carpeta completa y ejecutar `Quantum Gate_linux.sh` desde ella.
Incluye el motor; no requiere instalar Godot ni Blender.

Los datos del jugador se guardan por separado. No se distribuyen contraseñas,
partidas ni puntajes personales dentro de estos paquetes.

## Publicación

Adjuntar paquetes y `SHA256SUMS.txt` a una Release con su versión y pruebas.
La carpeta local `releases/` está excluida de Git: los ZIP se suben como adjuntos.
Conservar la Release anterior para poder volver a ella. No publicar el proyecto,
modelos editables, archivos Git, respaldos ni documentación interna.
