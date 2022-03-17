
El trabajo es un feed de Instagram con dos vistas, una con un mosaico de imágenes y otra con posts individuales. 

Está todo dentro de un div con clase "container-fluid" para que tome todo el ancho de la pantalla.

Arriba tiene un navbar con el logo de Instagram, un botón para crear un post y un botón con un menú desplegable. 
Al pulsar el botón de crear post se habre un modal con un cuadro de texto de tamaño adaptable, un botón de publicar y un botón de cancelar. El modal está creado con la clase "modal" y el role "dialog" de Bootstrap.

El botón con el menú desplegable tiene la clase "dropdown-toggle" y el menú desplegable con la clase "dropdown-menu" y un divider encima de la última opción.

Debajo de la navbar hay dos pills centradas para cambiar de una vista a otra del feed. Son botones con la clase "pill".

En la vista de mosaico (archivo index.html) hay tres rows con tres columnas de ancho 4 en cada una. Dentro de cada columna hay una imagen con su correspondiente alt.

En la vista de posts (archivo second.html) hay una serie de posts uno debajo de otro. Cada post es una card de Bootstrap con un header que incluye el título de la foto y la fecha del post, un card body con una imagen a ancho completo, los likes y la descripción de la foto, y por último un footer con el icono de like y texto de comment a la izquierda y un icon de elipsis vertical a la derecha. Para colocar los elementos del footer como quería metí los dos elementos de la izquierda en un div al que puse un float: left y luego puse un float: right al icono de la derecha. 

Todos los iconos son de FontAwesome y la fuente es de la familia roboto, sacada de Google Fonts.

# ![4Geeks Logo](http://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=4geeks,16) HTML Hello

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/html-hello.git)

The most basic boilerplate for any 4Geeks Academy student using the [gitpod.io](gitpod.io) coding editor.

[![How to open html/css preview of my project in gitpod](https://github.com/4GeeksAcademy/Templates-Boilerplates/blob/master/assets/hello-html-intro.png?raw=true)](https://youtu.be/dfbDCMu_p-0)

## What to do next?

Create an `index.html` file with the [basic HTML structure](http://content.breatheco.de/lesson/what-is-html-learn-html#page-structure) and see it live by running a web-server using the following command:

```sh
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```


