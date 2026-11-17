# Alchemy DX2 LAB

**Ocho herramientas para tu biblioteca DJ, reunidas en una sola aplicación para Mac.**

Alchemy DX evolucionó a **Alchemy DX2 LAB**: una suite para organizar bibliotecas, preparar crates y exportaciones USB/SD, crear playlists de eventos, editar metadatos y respaldar tu música y biblioteca de Serato.

## Versión actual: 1.0 — build 744

**Beta estable en la etapa final de pruebas previa al lanzamiento oficial.** Disponible únicamente para **Apple Silicon (ARM64, M1 o posterior)** y **macOS 14 Sonoma o posterior**. Interfaz en **español e inglés**.

**No hay versión Intel ni instalador Universal de LAB.** Las publicaciones antiguas de Alchemy DX se conservan como historial y no son la versión actual de esta suite.

[**Descargar Alchemy DX2 LAB 1.0 Beta — build 744 (ARM64)**](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.0.0-lab-build744/Alchemy.DX2.LAB.1.0.Beta.build.744.dmg)

[Ver novedades e instrucciones de esta versión](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.0.0-lab-build744)

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

## Novedades del build 744 frente a la beta 600

- **Toda la suite integrada:** ocho herramientas dentro de una misma aplicación, con una experiencia común; no necesitas abrir aplicaciones separadas para cada tarea.
- **Duplicate Finder:** nueva herramienta para localizar duplicados de audio y video y revisar versiones de una misma canción.
- **Library Manager ampliado:** reproducción desde cada fila, columnas y filtros, comentarios editables, edición de tags por lote, estado de salud de la biblioteca, nuevos crates en Serato y consulta de reproducciones.
- **Tags por lote con carátulas:** revisa los cambios antes de escribirlos y utiliza las opciones de restauración disponibles.
- **File Fix:** nuevo nombre de Golden Unlock, para identificar mejor su función con archivos bloqueados o de solo lectura.
- **Controles uniformes:** barra superior común, iconos propios por herramienta, acción principal en verde, «Detener» en rojo y reproductores que empiezan desde el inicio de la canción.
- **Operaciones recuperables:** los archivos apartados se guardan en una carpeta visible del mismo disco, con «Deshacer» y «Mostrar en el Finder»; Cleaner sigue enviando los archivos auxiliares `._` a la Papelera.
- **Más fluidez:** tablas y ventanas de opciones más ligeras; se concentra el trabajo en la herramienta abierta.
- **Mayor protección de datos:** mejoras en clonados, sincronización de USB, deshacer y manejo de permisos en discos compartidos.
- **Interfaz adaptable:** español e inglés, ajustes de tamaño de letra y densidad, paneles plegables y temas claro y grafito.

LAB es una aplicación aparte; no sustituye automáticamente a Alchemy DX 1.3 ni a las otras aplicaciones individuales.

## Instalar y empezar

1. En Apple  → **Acerca de esta Mac**, comprueba que tienes un chip Apple y **macOS 14 o posterior**.
2. Descarga el **.dmg** del build 744 desde el enlace de arriba.
3. Cierra LAB si está abierta. Abre el DMG y arrastra **Alchemy DX2 LAB** a **Aplicaciones**. Sustituye una instalación anterior de LAB si corresponde.
4. Antes del primer uso, lee **«LEER PRIMERO – Atención beta testers»** y las instrucciones incluidas en el instalador.
5. Abre la aplicación desde Aplicaciones. Cierra **Serato DJ y Rekordbox** antes de utilizar herramientas que escriban en tu biblioteca.
6. Elige una herramienta y comienza con copias de archivos y una USB de prueba.

La aplicación está firmada localmente y **no está notarizada por Apple**. Si macOS bloquea su apertura, revisa el aviso y las instrucciones incluidas en el instalador antes de decidir si quieres abrirla.

**Source code (zip)** y **Source code (tar.gz)** son archivos que GitHub genera con la documentación pública del repositorio. **No son instaladores.**

## Condiciones de esta beta

**La beta build 744 funciona hasta el 11 de enero de 2027.** Al caducar, las herramientas que escriben en Serato, en tus discos o en tus archivos dejan de funcionar hasta instalar una nueva versión; no se borran tus datos.

Aunque esta publicación corresponde a la beta estable actual, sigue siendo software beta y puede presentar errores. Haz copias de seguridad de tu música y biblioteca de Serato, revisa las operaciones propuestas y prueba las exportaciones en tu equipo antes de usarlas en una presentación.

La compatibilidad depende del equipo, firmware, formato de biblioteca y software utilizado. No se garantiza compatibilidad con todos los dispositivos Pioneer DJ / AlphaTheta ni con todas las versiones de Serato.

## Ayuda y soporte

Consulta el manual desde el menú **Ayuda**. Para reportar una incidencia, utiliza **Ayuda → Diagnóstico → Generar informe de diagnóstico…** y describe qué hiciste y qué ocurrió.

**Soporte:** [alchemydx2@gmail.com](mailto:alchemydx2@gmail.com).

Desarrollado por **DJ Bismarck · Costa Rica**. Alchemy DX2 LAB no está afiliada a Serato, Pioneer DJ, AlphaTheta ni Rekordbox; las marcas pertenecen a sus respectivos titulares.

Este repositorio distribuye instaladores compilados e información pública. No contiene el código fuente ni los proyectos de desarrollo. [Consultar el historial de publicaciones](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases).
