 # Proceso de Diseño de la web: Netflix Trivia

   Para elegir el tema de la trivia, nos inclinamos hacia el sector entretenimiento, consideramos música , series y películas.
   Teniendo en cuenta el contexto actual, en el que más personas tienen acceso a recursos audiovisuales y plataformas de este tipo, por ejemplo, la plataforma Netflix duplicó sus suscriptores en la cuarentena global.Es por ello que decidimos realizar una trivia sobre Netflix.

## PROTIPO DE BAJA FIDELIDAD
 En primer lugar elaboramos el Prototipo de baja fidelidad, de acuerdo a como creímos que se vería mejor y sería factible programar. Para ello elaboramos sketches con 4 pantallas:
 <br/>
  *1)* [Prototipo baja fidelidad pantallas 1,2](PrototipoBaja1.jpg)
  <br/>
  *2)* [Prototipo baja fidelidad pantallas 3,4](PrototipoBaja2.jpg)
       
## PROTIPO DE ALTA FIDELIDAD
Para pasar nuestro prototipo de baja a alta fidelidad, realizamos preguntas a algunos de nuestros amigos y familiares, que principalmente nos dieron como feedback:
- Que el botón de play diga "Play" debajo del botón, ya que si lo colocábamos encima o al lado, podrían parecer botones distintos.
- Colocar el simbolo de Netflix en vez de Imagenes de series y películas.
- Que utilicemos los colores caracterpisticos de Netflix y no otros.
- Que utilicemos imágenes grandes alusivas a las series y películas, en vez de colocar explícitamente el nombre.
- Que de jugar la trivia, la mayoría lo haría desde su computadora o PC.

De esta forma,continuamos en Figma, trabajando conjuntamente en la elaboración de 5 frameworks cuyo enlace es:
 ("https://www.figma.com/file/GI6YAtZKnHIYK7fg3CCTZG/First-job?node-id=26%3A2")
  

# LENGUAJES DE MARCADO
## HTML5
La estructura es la estructura similar pero con dos lineas particulares que significan:
<!DOCTYPE html> <!--Etiqueta no tiene inicio o cierre
<html lang="es"><!--Etiqueta de apertura, lang="es" (es un atributo)=> significa lenguaje español-->
  <head><!--contiene informacion general como <meta>;<Title>;<link> en este proyecto tiene:-->
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Trivia</title>
    <link rel="stylesheet" href="Trivia.css"><!--  rel= Crea un hipervínculo ; href= atributo de vincular a css en este caso-->

### Division por bloques
En esta parte del HTML, usamos:
   * div id= ; etiqueta y define una división en este programa divide la pantalla de bienvienda a pantalla de elegir categorias tambien divide la pantalla de preguntas de series y peliculas
   * id="screen1"; atributo especifica una identificación única en este caso "screeen1"  es la identificacion para la pantalla de bienvenida.

### Alineacion de textos
En varias lineas usamos <br> etiqueta para ingresar saltos de línea.

### Formulario

<form> usamos esta etiqueta para crear formularios, cada <form> tiene un <id> en nuestro caso hay 6 con sus respectivos <id>. Dentro de <form> hay <input type="radio" id="answer1" name="grupoA" value="incorrecto>
<input type = "radio"> : <input>etiqueta especifica un campo de entrada donde el usuario puede ingresar datos de varios tipos en nuestro caso un <input type = "radio"> Define un botón en el que se puede hacer clic.
Por ejemplo

<input type="radio"> Maria Pedrasa

<input type="radio">Ester Esposito

<input type="radio"> Danna Paola


# JAVASCRIPT
Declaramos variables y ocultamos screens 2 al 5, con style.display

Usamos function:
function play(){}
function series(){}
function peliculas(){}
function score(){}

# CSS
Usamos body
 1.background-color: black
 2.height:100%
 3.margin: 0
 4.display: flex
 5.flex-direction: column
    
- Los anteriores mencionados son atributos que recibira toda la pantalla de bienvenida.
- Los colores definidos  en cada pantalla ha sido negro buscando lograr el prototipo de alta fidelidad.
- El texto son centrados con [text-align]
- Los colores del texto son blancos[color:white] para resaltar en fondo negro[background-color:black] 
