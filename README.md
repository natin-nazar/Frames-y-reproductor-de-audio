# Proyecto: Frames y Reproductor de Audio

Este proyecto demuestra el uso de **iframes** para incrustar contenido multimedia (un video y un audio) en una página HTML. Incluye el diseño del frame mediante CSS, y un reproductor de audio que utiliza un archivo de audio libre de copyright. Se realiza también la acreditación del material multimedia utilizando la etiqueta `abbr`.

## Características

### 1. Uso de iframe para Incrustar un Video Externo

Se ha implementado un `<iframe>` en HTML para mostrar un video externo dentro de un marco en la página. El iframe se personaliza con los siguientes atributos obligatorios:

- **src**: URL del video a incrustar.
- **title**: Proporciona un título descriptivo para accesibilidad.

Los estilos CSS aplicados al iframe permiten:

- Definir el ancho y alto del marco.
- Modificar el estilo de borde del iframe.

### 2. Reproductor de Audio con Audio de Copyright Libre

Se incluye un segundo `<iframe>` que contiene un reproductor de audio con un archivo de audio libre de derechos de autor. La fuente del audio se acredita de forma adecuada en la página, utilizando la etiqueta `<abbr>`.

### 3. Acreditación con la Etiqueta `<abbr>`

Para acreditar los medios utilizados en este proyecto, se usa la etiqueta `abbr` con el atributo `title`. Esto permite proporcionar una explicación adicional cuando el usuario coloca el cursor sobre el texto de la acreditación.
