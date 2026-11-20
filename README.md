# Alchemy DX2 LAB

**Ocho herramientas para tu biblioteca DJ, reunidas en una sola aplicación para Mac.**

Alchemy DX evolucionó a **Alchemy DX2 LAB**: una suite para organizar bibliotecas, preparar crates y exportaciones USB/SD, crear playlists de eventos, editar metadatos y respaldar tu música y biblioteca de Serato.

## Versión actual: 1.0 — build 889

**Beta estable en la etapa final de pruebas previa al lanzamiento oficial.** Disponible únicamente para **Apple Silicon (ARM64, M1 o posterior)** y **macOS 14 Sonoma o posterior**. Interfaz en **español e inglés**.

**No hay versión Intel ni instalador Universal de LAB.** Las publicaciones antiguas de Alchemy DX se conservan como historial y no son la versión actual de esta suite.

[**Descargar Alchemy DX2 LAB 1.0 Beta — build 889 (ARM64)**](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.0.0-lab-build889/Alchemy.DX2.LAB.1.0.Beta.build.889.dmg)

[Ver novedades e instrucciones de esta versión](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.0.0-lab-build889)

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

## Novedades del build 889

- **Cues DX en Tags:** coloca hot cues A–E desde el beatgrid de Serato en MP3 y videos MP4, con separación de 2, 4 u 8 compases o automática según el género. Incluye Realinear, Completar, Reemplazar y Deshacer. Analiza primero en Serato y después pon los cues.
- **Exportación USB Normal o Turbo:** nuevo motor propio con alternativa automática si hace falta. «Adelantar el análisis para tus USB» prepara las canciones tras sincronizar; Alchemy DX, Playlist Creator y Library Manager comparten la misma ventana de exportación y formateo.
- **Library Manager:** «Lo que tocas» reúne más tocadas, últimos meses, sesiones y nunca tocadas. Salud muestra crates vacíos y copias en otro disco; detección de discos conectados y nuevas opciones de tags por lote.
- **Tags:** etiquetas desde el nombre del archivo, carátulas propias, recetas guardadas y exportables, limpieza selectiva de álbum o comentario y mejor compatibilidad con MP4 e ID3v2.2.
- **Data Back:** detección automática de discos, selección de varios crates y aviso de espacio insuficiente antes de clonar.
- **Toda la suite:** ventanas de opciones adaptables, controles más claros, ayudas al detener el puntero, progreso con tiempos y protección ante el agotamiento de memoria. Manual y ayuda en español e inglés.

## Pruebas documentadas de la beta 889

Según el informe de esta beta: **1.358 pruebas automáticas sin fallos**, **821 clics sin cierres**, dos rondas de estrés de un minuto sin cierres ni cuelgues y **más de 11.000 variaciones de Cues DX**. La exportación USB se comparó byte a byte con la referencia validada y resultó idéntica con tres motores; se revisaron crates, beatgrid, hot cues y cortes en FAT32.

También se documentaron 67 capturas de las ocho herramientas, sin redibujos en reposo ni avisos en consola, y más de 5.300 textos en español e inglés. Las pruebas utilizan copias y unidades simuladas. Estos resultados corresponden a los escenarios probados y no garantizan ausencia de errores en todos los equipos.

[Ver todas las novedades, pruebas y notas en español e inglés](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.0.0-lab-build889)

LAB es una aplicación aparte; no sustituye automáticamente a Alchemy DX 1.3 ni a las otras aplicaciones individuales.

## Instalar y empezar

1. En Apple  → **Acerca de esta Mac**, comprueba que tienes un chip Apple y **macOS 14 o posterior**.
2. Descarga el **.dmg** del build 889 desde el enlace de arriba.
3. Cierra LAB si está abierta. Abre el DMG y arrastra **Alchemy DX2 LAB** a **Aplicaciones**. Sustituye una instalación anterior de LAB si corresponde.
4. Antes del primer uso, lee **«LEER PRIMERO – Atención beta testers»** y las instrucciones incluidas en el instalador.
5. Abre la aplicación desde Aplicaciones. Cierra **Serato DJ y Rekordbox** antes de utilizar herramientas que escriban en tu biblioteca.
6. Elige una herramienta y comienza con copias de archivos y una USB de prueba.

La aplicación está firmada localmente y **no está notarizada por Apple**. Si macOS bloquea su apertura, revisa el aviso y las instrucciones incluidas en el instalador antes de decidir si quieres abrirla.

**Source code (zip)** y **Source code (tar.gz)** son archivos que GitHub genera con la documentación pública del repositorio. **No son instaladores.**

## Condiciones de esta beta

**La beta build 889 funciona hasta el 11 de enero de 2027.** Al caducar, las herramientas que escriben en Serato, en tus discos o en tus archivos dejan de funcionar hasta instalar una nueva versión; no se borran tus datos.

Aunque esta publicación corresponde a la beta estable actual, sigue siendo software beta y puede presentar errores. Haz copias de seguridad de tu música y biblioteca de Serato, revisa las operaciones propuestas y prueba las exportaciones en tu equipo antes de usarlas en una presentación.

La compatibilidad depende del equipo, firmware, formato de biblioteca y software utilizado. No se garantiza compatibilidad con todos los dispositivos Pioneer DJ / AlphaTheta ni con todas las versiones de Serato.

## Ayuda y soporte

Consulta el manual desde el menú **Ayuda**. Para reportar una incidencia, utiliza **Ayuda → Diagnóstico → Generar informe de diagnóstico…** y describe qué hiciste y qué ocurrió.

**Soporte:** [alchemydx2@gmail.com](mailto:alchemydx2@gmail.com).

Desarrollado por **DJ Bismarck · Costa Rica**. Alchemy DX2 LAB no está afiliada a Serato, Pioneer DJ, AlphaTheta ni Rekordbox; las marcas pertenecen a sus respectivos titulares.

Este repositorio distribuye instaladores compilados e información pública. No contiene el código fuente ni los proyectos de desarrollo. [Consultar el historial de publicaciones](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases).
