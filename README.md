# TP4 y TP5 - PowerFit Gym

Trabajo Práctico N°4 y N°5 de Laboratorio de Programación. Sitio web de un gimnasio hecho con HTML y CSS.

## Páginas

- index.html: inicio
- nosotros.html: historia y horarios del gimnasio
- galeria.html: fotos de las instalaciones
- contacto.html: datos de contacto
- impacto.html: tabla con los datos de la jornada "ReConversar" (TP5)

## Tabla de impacto.html (TP5)

La tabla usa thead, tbody y tfoot, con caption explicando de qué se trata. Usa rowspan para agrupar el nombre de la organización en las 3 filas de meses, y colspan para agrupar "Métricas de Limpieza" arriba de las columnas de metros y voluntarios.

En el CSS le agregué:
- border-collapse: collapse y padding para que se vea prolija
- filas cebra con :nth-child(even) y :nth-child(odd)
- un hover en las filas para resaltar la que se está leyendo
- el tfoot con fondo oscuro para que se note que es el total

## Cómo usé los estados de los links

En el archivo estilos.css le puse estilo a los 4 estados de los enlaces para que no se vean como los de por defecto del navegador:

- link: el color normal del enlace (naranja)
- visited: un color un poco más oscuro para cuando ya lo clickeaste
- hover: cambia de color y se subraya cuando pasás el mouse por encima, así el usuario sabe que puede hacer click
- active: un color más oscuro todavía, para el momento justo en que se hace click

También hice que el menú de navegación marque con la clase .activo en qué página está parado el usuario, para que sea más fácil ubicarse (como dice Steve Krug, que el usuario no tenga que pensar dónde está).

Y agregué un enlace con pinta de botón (clase .boton) usando padding, background-color y sacando el subrayado con text-decoration: none.

## Imágenes

Las fotos de la galería son de internet (Pexels), no están guardadas en la carpeta del proyecto.
