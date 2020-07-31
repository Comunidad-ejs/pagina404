# Reto 1 Pagina404

El reto consiste en que crees una pagina 404, si estas haciendo el proyecto de la escuela de javascript de platzi, puedes crearla para platzi video. Si no, para cualquier otro proyectos.

## Recomendaciones

realiza un fork al proyecto y ejecuta el reto, despues envia un pull recquest con la solucion.

### El curso recomendado para el reto de platzi es:

https://platzi.com/cursos/frontend-developer/

### Algunas URL de interes
https://css-tricks.com/snippets/css/complete-guide-grid/
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://developer.mozilla.org/es/docs/Web/CSS/grid

### Recueda 
![display](assets/image.png)

### te dejo algunas url de ejercicios que te ayudaran a resolver el reto

https://cssgridgarden.com/#es
https://flexboxfroggy.com/#es
http://www.flexboxdefense.com/


## Condiciones:

[] Debes utilizar Display Grid o Flex para acomodar los elementos
[] Debe ser responsive la pagina (verse bien en cualquier dispositivo)

## Ejemplo
![Ejemplo](assets/Captura.PNG)



Si quieren mejorar el proyecto o tienen cualquier aporte o duda no duden con contactarmen https://twitter.com/alejozepol estoy para ayudarles.

## Solución 
Decidí usar el reto para practicar con CSS-grid-layout, por lo mismo la mayoria de los displays tienen asignado grid.

### body
En la etiqueta body ingresó un gradiant al background generado en https://cssgradient.io/. 
Se ingreso un height minimo de 100vh, quitando margin y pading.
Se agregó una font aleatoria.
Se designo un color general de fuente de `white`
Se agrego el display grid con template-rows de `100px 1fr 100px`. 

### header
Se adicionó el display grid para alargar el tag hijo mediante `justify-items: stretch;` a todo el campo que ocupaba, y dando un padding horizontal de 20px.
la etiqueta nav se ajustó vertical mediante el margin.

Se designo un contenedor para la imagen para controlar su alto, y la imagen quedó con un alto heredado.


### main
El tag main recibió un display grid.
Se designo un contenedor para los textos al que se agregó la clase `.not_found`, el cual se alineó de manera vertical.
Los textos se alinearon con `align-text: center;`

### footer
El tag footer recibió un display grid para alinear a su hijo en el centro y generar un padding horizontal
El tag ul se le quitaron los estilos y margenes y se le estableció un `display: flex;`, aqui si fue porque facilitaba mucho el cambio en el responsive, por esto mismo al tener un espacio pequeño se le dio el wrap para que se ajustara automaticamente `flex-wrap: wrap;`.
A los links se les dio el color blanco y se les quitó la decoracion, asi mo se le estableció un margin a la derecha para dar organización visual, y finalmente se le dio un hover underline.


