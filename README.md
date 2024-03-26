# videos_css

- Los videos no tienen proque ser los mismos, buscándolos en Youtube, eligiendo la opción compartir > insertar > copiar el código HTML, que luego podemos modificar (pro ejemplo, poner el ancho y alto en CSS)
- El fondo es un degradado. Para que ocupe toda la página debemos hacer lo siguiente:
  -   Crear un estilo para la etiqueta html con un height del 100%
  -   Crear un estilo para la etiqueta body con background-attachment: fixed; background-repeat: no-repeat; y height: 100%;
-   Para las estrellas podéis crear clases CSS que muestre las estrellas correspondientes cambiando un width donde la estrella esté de imagen de fondo (la estrella ocupa 24px), repitiendo el fondo
-   Entre el video y el título puede quedar una separación inferior. Esto es debido a que el iframe es de tipo inline y deja ese espacio. Una solución es usar display:block en el iframe.

Efectos a realziar:
- al pasar el ratón sobre el enlace + información, el color de fondo debe cambiar a un azul más claro

Se han añadido dos soluciones:
- una con display: inline-block
- una con Flexbox

  
