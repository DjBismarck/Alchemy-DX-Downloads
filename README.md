# Alchemy DX2 LAB

**Ocho herramientas para tu biblioteca DJ, reunidas en una sola aplicación para Mac.**

Alchemy DX evolucionó a **Alchemy DX2 LAB**: una suite para organizar bibliotecas, preparar crates y exportaciones USB/SD, crear playlists de eventos, editar metadatos y respaldar tu música y biblioteca de Serato.

## Versión actual: 1.0 — build 1184

**Beta estable en la etapa final de pruebas previa al lanzamiento oficial.** Disponible para **Apple Silicon (ARM64)** y en instalador **Universal (Apple Silicon e Intel)**, con **macOS 14 Sonoma o posterior**. **La versión Intel está en pruebas.** Interfaz en **español e inglés**.

Elige **ARM64** si tu Mac tiene chip Apple, o **Universal** si tiene procesador Intel. Las publicaciones anteriores se conservan como historial.

[**Descargar Alchemy DX2 LAB 1.0 Beta — build 1184 (ARM64)**](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.0.0-lab-build1184/Alchemy.DX2.LAB.1.0.Beta.build.1184.dmg)

[**Descargar build 1184 Universal — Apple Silicon e Intel (Intel en pruebas)**](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.0.0-lab-build1184/Alchemy.DX2.LAB.1.0.Beta.build.1184.Universal.dmg)

[Ver novedades e instrucciones de esta versión](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.0.0-lab-build1184)

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

## Novedades del build 1184

- **Tags abre correctamente con monitor externo:** corregido el bloqueo que podía ocurrir al iniciar LAB directamente en Tags en español. Los filtros se adaptan al ancho disponible.
- **Más fluidez al redimensionar Tags:** el informe documenta más del doble de fluidez en los escenarios medidos, también con bibliotecas grandes. El resultado depende del equipo.
- **Ocultar LAB sin cierres inesperados:** corregido el cierre que podía ocurrir al ocultar la aplicación mientras terminaba de cerrarse una hoja o panel.
- **Library Manager más sólido:** barra lateral de Salud y «Lo que tocas» más estable, con filas visibles y un indicador mientras se calculan los conteos.
- **Diagnóstico de bloqueos:** el informe identifica cuánto duró la falta de respuesta, en qué herramienta ocurrió y dónde se detuvo; también recoge avisos de macOS.
- **Controles más legibles:** los botones de lote de Tags se adaptan a letra grande y ventanas pequeñas; mejoras en el Historial de Tags y Ajustes de Library Manager, y textos de almacenamiento en inglés uniformes.
- **Desde la beta 1166:** scratch con videos, mezclas largas y formatos de audio; ondas de archivos largos que se dibujan progresivamente; Riddims en Tags; Ajustes → Almacenamiento; ancho de columnas con doble clic y letras sueltas que ya no cambian de canción.

## Pruebas documentadas de la beta 1184

**1.764 pruebas automáticas sin fallos · 850 clics de recorrido por la aplicación sin cierres · exportación USB idéntica byte a byte con tres motores.**

Estas cifras proceden del informe de esta build. Describen los escenarios probados y no garantizan ausencia de errores en todas las configuraciones. La distribución Universal incluye Intel, que continúa en pruebas.

## Manuales ilustrados y comprobación del instalador

- [Manual ilustrado en español (PDF, 40 páginas)](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.0.0-lab-build1184/Manual.ilustrado.-.Alchemy.DX2.LAB.Beta.pdf)
- [Illustrated Guide in English (PDF, 40 pages)](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.0.0-lab-build1184/Illustrated.Guide.-.Alchemy.DX2.LAB.Beta.pdf)

Los manuales muestran capturas de la **build 1166** y explican las ocho herramientas, los botones, los pasos y los atajos. Consulta las notas de la 1184 para los cambios posteriores.

En los archivos de la publicación encontrarás también los **SHA-256 de ARM64 y Universal** para comprobar la integridad de tu descarga. Los archivos de sumas conservan los nombres originales de los instaladores; GitHub sustituye los espacios y paréntesis por puntos al descargarlos.

[Ver todas las novedades e instrucciones en español e inglés](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.0.0-lab-build1184)

LAB es una aplicación aparte; no sustituye automáticamente a Alchemy DX 1.3 ni a las otras aplicaciones individuales.

## Instalar y empezar

1. En Apple  → **Acerca de esta Mac**, comprueba si tienes un chip Apple o procesador Intel y **macOS 14 o posterior**.
2. Descarga el **.dmg** del build 1184 desde el enlace de arriba.
3. Cierra LAB si está abierta. Abre el DMG y arrastra **Alchemy DX2 LAB** a **Aplicaciones**. Sustituye una instalación anterior de LAB si corresponde.
4. Antes del primer uso, lee **«LEER PRIMERO – Atención beta testers»** y las instrucciones incluidas en el instalador.
5. Abre la aplicación desde Aplicaciones. Cierra **Serato DJ y Rekordbox** antes de utilizar herramientas que escriban en tu biblioteca.
6. Elige una herramienta y comienza con copias de archivos y una USB de prueba.

La aplicación está firmada localmente y **no está notarizada por Apple**. Si macOS bloquea su apertura, revisa el aviso y las instrucciones incluidas en el instalador antes de decidir si quieres abrirla.

**Source code (zip)** y **Source code (tar.gz)** son archivos que GitHub genera con la documentación pública del repositorio. **No son instaladores.**

## Condiciones de esta beta

**La beta build 1184 funciona hasta el 11 de enero de 2027.** Al caducar, las herramientas que escriben en Serato, en tus discos o en tus archivos dejan de funcionar hasta instalar una nueva versión; no se borran tus datos.

Aunque esta publicación corresponde a la beta estable actual, sigue siendo software beta y puede presentar errores. Haz copias de seguridad de tu música y biblioteca de Serato, revisa las operaciones propuestas y prueba las exportaciones en tu equipo antes de usarlas en una presentación.

La compatibilidad depende del equipo, firmware, formato de biblioteca y software utilizado. No se garantiza compatibilidad con todos los dispositivos Pioneer DJ / AlphaTheta ni con todas las versiones de Serato.

## Ayuda y soporte

Consulta el manual desde el menú **Ayuda**. Para reportar una incidencia, utiliza **Ayuda → Diagnóstico → Generar informe de diagnóstico…** y describe qué hiciste y qué ocurrió.

**Soporte:** [alchemydx2@gmail.com](mailto:alchemydx2@gmail.com).

Desarrollado por **DJ Bismarck · Costa Rica**. Alchemy DX2 LAB no está afiliada a Serato, Pioneer DJ, AlphaTheta ni Rekordbox; las marcas pertenecen a sus respectivos titulares.

Este repositorio distribuye instaladores compilados e información pública. No contiene el código fuente ni los proyectos de desarrollo. [Consultar el historial de publicaciones](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases).
