# Reto Freelancer
***

Para este reto se pidio replicar (maquetado non responsive ) la pagina "Freelancer", el resultado debía ser el siguiente:

![Freelancer Website](docs/fullpage.png)
## Flujo de trabajo

Para empezar, en mi archivo .html linkee mi main.css, Font Awesome(con sus respectivos tamaños ya predeterminados por la página) y las fuentes Montserrat y Lato.
 Luego dividí mi pagina en 5 cajas principales (divs) que me ayudarían a previzualizar la distribución de los elementos en la pagina.
 A cada div caja principal (nombrados firsbox, secondbox, thirdbox etc...)les asigné un color de fondo llamativo (rojo, azul, verde) que me servía para poder ajustar las dimensiones. Una vez logradas las medidas, quitaba el color de fondo guía.
 Creé el header con una lista desordenada, luego el resto del cuerpo con la primera caja principal.
 Para afrontar el problema de la estrella entre lineas, hice tres span dentro de un div, dos para las lineas y uno para la estrella.
 La parte del portafolio es mi caja 2, para posicionar las imagenes las puse en divs con posición absoluta. 
 Para el efecto de hover que muestra otra imágen use el atributo "onmouseover", que se activa cuando el puntero del ratón pasa sobre la imagen. Ejemplo de sintaxis:

####Mouse sobre el gatito Pusheen para ver el efecto.
####HTML code
```html 
<img name= "PusheenPothaa"src="assets/images/Pusheenpotah" onmouseOver="alert('¡Es Leviósa no Leviosaaaaá!)">
```
 
< img name= "imagen1"src="images/logo.gif" onmouseOver="alert('¡Es Leviósa no Leviosaaaaá!)">

La parte about es mi caja 3, el texto esta en un div con 2 columnas asignadas en el css. 

Para el formulario seguí las instruccipones de W3schools:

[Cómo hacer formularios por w3school](https://www.w3schools.com/css/css_form.asp "Formularios")

Para hacer los botones, me guié con mi trabajo "Tipografias-e-iconos".
Para los iconos de Font Awesome rodeados por un círculo, llegué a su página de ejemplos donde estaba el código para hacerlo.

[Icónos en circulos de Font Awesome](http://fontawesome.io/examples/ "iconos en circulos")

Además encontré este ejemplo muy explicativo de como aplicar el código.

[Ejemplo](http://jsfiddle.net/sampatbadhe/ocftsLfe/ "ejemplo")

Para finalizar, revisé mi código HTML en [Validador de HTML, freeformatter](https://www.freeformatter.com/html-validator.html "validador HTML") y mi código CSS en [Validador de CSS, Jigsaw.w3](https://jigsaw.w3.org/css-validator/#validate_by_inputl "validador CSS").