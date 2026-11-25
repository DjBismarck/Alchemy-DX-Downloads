# Alchemy DX2 LAB

**Ocho herramientas para tu biblioteca DJ, reunidas en una sola aplicación para Mac.**

Alchemy DX evolucionó a **Alchemy DX2 LAB**: una suite para organizar bibliotecas, preparar crates y exportaciones USB/SD, crear playlists de eventos, editar metadatos y respaldar tu música y biblioteca de Serato.

## Versión actual: 1.0 — build 1120

**Beta estable en la etapa final de pruebas previa al lanzamiento oficial.** Disponible únicamente para **Apple Silicon (ARM64, M1 o posterior)** y **macOS 14 Sonoma o posterior**. Interfaz en **español e inglés**.

**No hay versión Intel ni instalador Universal de LAB.** Las publicaciones antiguas de Alchemy DX se conservan como historial y no son la versión actual de esta suite.

[**Descargar Alchemy DX2 LAB 1.0 Beta — build 1120 (ARM64)**](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.0.0-lab-build1120/Alchemy.DX2.LAB.1.0.Beta.build.1120.dmg)

[Ver novedades e instrucciones de esta versión](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.0.0-lab-build1120)

## Las ocho herramientas

| Herramienta | Qué puedes hacer |
| --- | --- |
| **Alchemy DX** | Convertir carpetas en crates de Serato y preparar USB o SD para determinados equipos Pioneer DJ / AlphaTheta compatibles, sin pasar por Rekordbox. |
| **Library Manager** | Gestionar la biblioteca de Serato por disco y trabajar con una USB enlazada a tus crates. |
| **Playlist Creator** | Preparar el crate de un evento a partir de una lista de Spotify, Apple Music o texto, revisando las versiones de las canciones propuestas. |
| **Duplicate Finder** | Encontrar canciones y videos repetidos y versiones de una misma canción; apartar las copias elegidas a una carpeta recuperable. |
| **Tags** | Revisar y corregir año, género y otros metadatos de canciones y videos, con respaldo y restauración por lote. |
| **Data Back** | Clonar o respaldar la biblioteca de Serato, o crates seleccionados, en un disco externo con verificación. |
| **File Fix** | Quitar el candado dorado asociado a archivos de solo lectura en Serato. |
| **Cleaner** | Buscar archivos auxiliares de macOS `._` y enviarlos a la Papelera. |

Las listas de Spotify y Apple Music se utilizan para preparar playlists: no se ofrece descarga de música desde esos servicios.

## Novedades del build 1120

- **Reproductor DX:** deck con carátula, BPM del tramo, tiempo restante, distancia al siguiente cue, pads 1–8 y ondas general y ampliada. Columna «Onda» con cues y loops en Library Manager, Alchemy DX y Duplicate Finder.
- **Loops en golpes:** 1, 2, 4, 8, 16 o 32 golpes, con 4 de inicio. Corregida la deriva entre vueltas. **Limitación conocida:** todavía puede oírse un corte muy breve al cerrar el loop.
- **Q y salto por golpes:** cuantización de pads y saltos durante la reproducción; controles reorganizados y deck que adapta sus filas al ancho de la ventana.
- **Más fluidez:** el informe describe onda a 60 cuadros por segundo y carátulas entre 0,1 y 0,4 segundos en los escenarios medidos. El rendimiento depende del equipo y los archivos.
- **Alchemy DX:** lee metadatos completos de carpetas nuevas aunque Serato aún no las tenga y refleja cambios de Serato al volver a LAB o cerrar Serato.
- **USB:** progreso por canción, respaldo más claro y parada también durante el respaldo; mejoras al detectar memorias de otra Mac y al localizar música movida. Conservación de cues e historial del reproductor documentada para Legacy; el caso OneLibrary está pendiente de aclaración documental.
- **Serato DJ 5 y grillas:** lectura de su beatgrid, respeto de los pads ocupados por Cue Loops, editor de grilla con deshacer y análisis por lote.
- **Formatos y Tags:** edición de etiquetas dentro de WAV, AIFF y FLAC; preparación de audio compatible para determinados reproductores; carátulas de 1000 px, nombres y recetas más accesibles y restauración exacta de valores.
- **Suite integrada:** preescucha y volumen comunes, atajos uniformes, controles legibles con ventanas estrechas y mejor comportamiento entre monitores.

## Pruebas documentadas de la beta 1120

El informe de novedades registra **1.720 pruebas automáticas sin fallos**, **854 clics de recorrido sin cierres** y exportación USB **idéntica byte a byte con tres motores**. Estas cifras corresponden a los escenarios documentados y no garantizan ausencia de errores ni compatibilidad con todos los equipos.

[Ver novedades, límites conocidos e instrucciones en español e inglés](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.0.0-lab-build1120)

LAB es una aplicación aparte; no sustituye automáticamente a Alchemy DX 1.3 ni a las otras aplicaciones individuales.

## Instalar y empezar

1. En Apple  → **Acerca de esta Mac**, comprueba que tienes un chip Apple y **macOS 14 o posterior**.
2. Descarga el **.dmg** del build 1120 desde el enlace de arriba.
3. Cierra LAB si está abierta. Abre el DMG y arrastra **Alchemy DX2 LAB** a **Aplicaciones**. Sustituye una instalación anterior de LAB si corresponde.
4. Antes del primer uso, lee **«LEER PRIMERO – Atención beta testers»** y las instrucciones incluidas en el instalador.
5. Abre la aplicación desde Aplicaciones. Cierra **Serato DJ y Rekordbox** antes de utilizar herramientas que escriban en tu biblioteca.
6. Elige una herramienta y comienza con copias de archivos y una USB de prueba.

La aplicación está firmada localmente y **no está notarizada por Apple**. Si macOS bloquea su apertura, revisa el aviso y las instrucciones incluidas en el instalador antes de decidir si quieres abrirla.

**Source code (zip)** y **Source code (tar.gz)** son archivos que GitHub genera con la documentación pública del repositorio. **No son instaladores.**

## Condiciones de esta beta

**La beta build 1120 funciona hasta el 11 de enero de 2027.** Al caducar, las herramientas que escriben en Serato, en tus discos o en tus archivos dejan de funcionar hasta instalar una nueva versión; no se borran tus datos.

Aunque esta publicación corresponde a la beta estable actual, sigue siendo software beta y puede presentar errores. Haz copias de seguridad de tu música y biblioteca de Serato, revisa las operaciones propuestas y prueba las exportaciones en tu equipo antes de usarlas en una presentación.

La compatibilidad depende del equipo, firmware, formato de biblioteca y software utilizado. No se garantiza compatibilidad con todos los dispositivos Pioneer DJ / AlphaTheta ni con todas las versiones de Serato.

## Ayuda y soporte

Consulta el manual desde el menú **Ayuda**. Para reportar una incidencia, utiliza **Ayuda → Diagnóstico → Generar informe de diagnóstico…** y describe qué hiciste y qué ocurrió.

**Soporte:** [alchemydx2@gmail.com](mailto:alchemydx2@gmail.com).

Desarrollado por **DJ Bismarck · Costa Rica**. Alchemy DX2 LAB no está afiliada a Serato, Pioneer DJ, AlphaTheta ni Rekordbox; las marcas pertenecen a sus respectivos titulares.

Este repositorio distribuye instaladores compilados e información pública. No contiene el código fuente ni los proyectos de desarrollo. [Consultar el historial de publicaciones](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases).
