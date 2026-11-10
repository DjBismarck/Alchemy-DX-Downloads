# Alchemy DX

**Organización de bibliotecas DJ y exportación a USB para macOS**

Alchemy DX es una aplicación para Mac que te ayuda a organizar tu biblioteca musical, importar crates de Serato DJ y preparar exportaciones USB o SD para determinados equipos DJ compatibles.

**Idioma de la aplicación: español.** Actualmente no dispone de una opción para cambiar de idioma.

## Beta pública

- **Versión disponible:** 1.3 Beta — build 184.
- **Sistema requerido:** macOS 13 Ventura o posterior.
- **Plataforma principal:** Apple Silicon (ARM64).
- **Mac con Intel:** hay un instalador Universal. Su versión Intel se probó mediante Rosetta en Apple Silicon; todavía no se han confirmado pruebas en un Mac Intel físico.
- **Fecha límite de la beta:** 8 de enero de 2027. Al vencer, se desactivan la sincronización, las exportaciones a USB y Rekordbox y el formateo. Puedes seguir consultando la biblioteca y utilizando el Inspector.

Esta es una versión beta. Puede presentar errores y sus funciones o compatibilidad pueden cambiar. Conserva copias de seguridad y prueba las exportaciones con tu equipo antes de utilizarlas en una presentación.

## Descargar e instalar

Abre la [descarga de Alchemy DX 1.3 Beta — build 184](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/tag/v1.3-beta-build184) y busca la sección **Assets** (archivos).

### 1. Elige el instalador para tu Mac

Para saber qué Mac tienes, abre el menú Apple  y selecciona **Acerca de esta Mac**. Comprueba si indica un chip Apple o un procesador Intel.

| Tu Mac | Archivo que debes descargar |
| --- | --- |
| Apple Silicon (chip Apple) | [Alchemy.DX.1.3.Beta.build.184.dmg](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.3-beta-build184/Alchemy.DX.1.3.Beta.build.184.dmg) |
| Intel | [Alchemy.DX.1.3.Beta.build.184.Universal.dmg](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases/download/v1.3-beta-build184/Alchemy.DX.1.3.Beta.build.184.Universal.dmg), teniendo en cuenta la limitación de pruebas indicada arriba |

Descarga **solo uno** de los instaladores. Los enlaces **Source code (zip)** y **Source code (tar.gz)** son archivos que GitHub genera con la documentación pública del repositorio; no son instaladores de Alchemy DX.

### 2. Instala la aplicación

1. Abre el archivo **.dmg** que descargaste.
2. Sigue las instrucciones incluidas en el instalador. Si aparecen Alchemy DX y un acceso a Aplicaciones, arrastra **Alchemy DX** a **Aplicaciones**.
3. Abre **Alchemy DX** desde **Aplicaciones**.
4. Conserva una copia de seguridad de tu biblioteca y realiza una exportación pequeña de prueba antes de usarla habitualmente con tu equipo DJ.

Si macOS impide abrir la aplicación, revisa el mensaje del sistema y las notas de esta versión antes de continuar.

## Funciones principales

- **Organiza tu biblioteca:** administra carpetas, playlists y el orden de las canciones para exportar.
- **Importa tus crates de Serato:** incluye crates y subcrates, también con música distribuida entre discos conectados.
- **Prepara USB y tarjetas SD:** exporta para determinados equipos DJ compatibles y actualiza exportaciones existentes sin volver a formatear.
- **Elige cómo organizar las playlists:** conserva las carpetas o coloca las playlists en la raíz.
- **Escucha antes de exportar:** utiliza el reproductor con controles, portada y barra de avance.
- **Revisa tus exportaciones:** consulta la integridad de la biblioteca y los resultados con el Inspector USB/SD.
- **Trabaja con archivos de video:** extrae el audio durante la exportación USB cuando corresponda.
- **Sigue el progreso:** consulta las fases de la exportación, los tiempos y los mensajes de resultado.
- **Utiliza una interfaz adaptada a macOS:** apariencia Día, Noche o Auto, atajos de teclado y ayuda sin conexión.

La compatibilidad depende del equipo, su firmware, el sistema operativo, el formato de biblioteca y la versión del software. No se garantiza compatibilidad con todos los dispositivos Pioneer DJ ni con todas las versiones de Serato DJ. Haz una copia de seguridad del contenido de tus USB y tarjetas SD antes de actualizarlos o formatearlos.

## Novedades de 1.3 Beta — build 184

- **Cierres corregidos:** solucionados cierres inesperados al usar la rueda del ratón y al arrastrar pistas, presentes en los builds 175 y 178.
- **Mover canciones:** arrástralas a una carpeta de la barra lateral o usa «Mover a otra carpeta…». Esta acción mueve los archivos en el disco, solicita confirmación y se puede deshacer.
- **Papelera:** envía canciones a la Papelera con confirmación para poder recuperarlas.
- **Buscar duplicadas:** encuentra canciones con el mismo audio, aunque cambien el nombre o las etiquetas. Revisa las copias seleccionadas antes de decidir qué hacer con ellas.
- **Añadir a playlists:** arrastra canciones sobre una playlist de «Para exportación» para añadirlas sin mover los archivos originales.

En las playlists propias, quitar duplicadas de la playlist no borra sus archivos del disco.

Se recomienda actualizar desde los builds 175 y 178. Se mantienen la edición de etiquetas, el contador por carpeta, la preescucha y las funciones de exportación e Inspector USB/SD.

Antes de mover archivos o editar etiquetas, conserva copias de seguridad y cierra Serato DJ.

## Acerca de este repositorio

Este repositorio distribuye los instaladores compilados de Alchemy DX e información pública para quienes prueban la beta. No incluye el código fuente del producto ni los proyectos de desarrollo.

Puedes consultar todas las versiones publicadas en [Releases](https://github.com/DjBismarck/Alchemy-DX-Downloads/releases).
