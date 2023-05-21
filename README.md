# README

Este documento recoge las fases y objectivos de el proyecto "Parallax Scrolling Effect".
Crearemos una plantilla de un sidebar lateral que nos muestre las siguientes opciones: home, Tecnologías, Proyectos y contacto.

* Fecha: 17/03/23
* Fuente: [w3schools](https://www.w3schools.com/howto/howto_css_parallax.asp)
* Tecnologías: HTML / CSS / JAVASCRIPT
* Aclaraciones: [background-attachment: fixed](https://developer-mozilla-org.translate.goog/en-US/docs/Web/CSS/background-attachment?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es&_x_tr_pto=sc)


## FASES
1. HTML y CSS:
    1. Crearemos tres contenedores que harán el efecto parallax y los nombraremos con las clases parallax-1, parallax-2 y parallax-3, tendrán los estilos comunes de position relative, le daremos una opacidad para crear el efecto velo de las imagenes y background-attachment: fixed; que es la propiedad que nos permite fijar el fondo con la ventana gráfica. A cada una de estas clases por separad le daremos el height que queramos y le asignaremos la imagen de fondo.
    2. Los contenedores parallax los alternaremos con otros contenedores que serán los que contengan los textos, tendrán un color de fondo para que tenga un contraste con las imagenes y tendrán un position relative

## OBJECTIVOS
El objetivo para este proyecto es crear una plantilla que podamos implementar en futuros proyectos en los que necesitemos incorporar un contenido intercalado con imágenes de fondo.