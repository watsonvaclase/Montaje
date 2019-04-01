# Proyecto-TJBot
## Manual del ejercicio TJBot 
### 	PROYECTO TJBOT
<div id="texto1">En esta sección vamos a construir un TJBot con el que poder mantener una conversación. [6] </div>
<br> 
<br>
<div id="texto2">Para ello vamos a utilizar una Raspberry Pi3, la cual conectaremos a los servicios de conversación <br>
de Watson y así poder hacer hablar a nuestro robot.</div>
<br> 
<br>
<img id="img1" src="imagenes/Imagen1.png"> <br> <br>
<p id="texto3"> El objetivo final será hacer que nuestro TJBot sea capaz de mantener una conversación con nosotros y obedezca algunas órdenes.</p> <br> 
<b> 1.1.	CÓMO CREAR A TJBOT </b> <br> <br> 
<b> 1.1.1.	RAPSBERRY PI3 </b> <br> <br>
<div id="texto4">Raspberry Pi es un computador de placa única. <br> <br> <br>
Para trabajar con la Raspberry Pi3 vamos a necesitar un  <br>
monitor, un ratón, un teclado y una fuente de <br>
alimentación para trabajar con ella. También debemos <br>
tener una tarjeta micro SD con el sistema operativo <br>
instalado, en este caso trabajaremos con el sistema <br>
operativo Raspbian.</div> <br> <br>
<img id="img2"src="imagenes/Imagen2.png"> <br><br>
<div id="texto5"> Para crear nuestro TJBot hace falta conectar algunos componentes más a nuestra placa: </div>
<div id="lista"> 
<ul> 
<li>Un micrófono</li>
<li>Un altavoz</li>
<li>Una cámara</li>
<li>Un servomotor</li>
<li>LED</li>
</ul>
</div> <br> <br>
<b> 1.2.	MONTANDO A TJBOT </b> <br>
<div id="texto6"> 
Para comenzar a trabajar con TJBot, lo primero que debemos hacer es obtener las piezas para <br>
poder montarlo.
<br> <br>
Este robot es DY (Do it yourself) y puede conseguirse imprimiendo las piezas en una impresora <br>
3D. Las piezas que se deben imprimir pueden encontrarse en la siguiente web:
<br> <br> <br> 
<a href="https://ibmtjbot.github.io/#gettj"> https://ibmtjbot.github.io/#gettj</a> <br> <br> <br>
Las piezas que conseguiremos serán las siguientes: <br> <br>
<img src="imagenes/Imagen3.png" id="img3"> <br> <br> <br>
¿Cómo lo montamos? <br> <br> <br>
<div> Primero, insertamos las piernas en la mandíbula. Las piernas entran en los agujeros en forma de <br>
 L en la mandíbula. Inserta desde la parte superior de la mandíbula hacia abajo. </div> <br> <br> <br>
<img src="imagenes/Imagen4.png" id="img4"> <br> <br> <br>
<div> Después, cogemos la pieza "leg brace". Se encuentra en los dos orificios rectangulares en las <br>
patas debajo de la mandíbula. Mantiene las piernas rectas y soporta la mandíbula. Debemos <br>
 asegurar que esté orientada de modo que haga contacto con la parte inferior de la mandíbula. </div> <br> <br>
<img src="imagenes/Imagen5.png"id="img5"> <br> <br> <br>
<div> Ahora, cogemos los pies y los insertamos en las muescas de la pierna como se muestra a <br>
 continuación. Inserta los pies desde el exterior de cada pierna. </div> <br> <br> <br>
<img src="imagenes/Imagen6.png" id="img6"> <br> <br> <br>
<div> Si tenemos un servo motor, es hora de insertarlo en el orificio del lado izquierdo en la mandíbula. <br>
Cogemos el retenedor inferior y lo deslizamos hacia abajo a través de los agujeros en forma de L <br>
en las patas. Los brazos de soporte en la parte inferior de este retenedor deben caber en las <br>
 muescas de acoplamiento en la mandíbula. </div> <br> <br> <br>
<img src="imagenes/Imagen7.png" id="img7"> <br> <br> <br>
<div> A continuación, insertaremos la Raspberry Pi. Se monta boca abajo, con sus puertos expuestos a <br>
través de los tres agujeros en la mandíbula. <br> <br>
Si tenemos una cámara: tomamos el soporte de montaje de la cámara. Deslizamos los dos <br>
montajes laterales de la cámara en las muescas en la parte delantera del retenedor. Deslizamos <br>
la cámara Pi en el soporte y luego agregue los reforzadores superior y frontal para mantener la <br>
 cámara ajustada. </div> <br> <br> <br> 
<img src="imagenes/Imagen8.png" id="img8"> <br> <br> <br>
<div> El siguiente retenedor es el que tiene el pequeño círculo grabado en él. Lo añadimos a TJBot <br>
deslizándolo a través de los orificios en forma de L, con el círculo pequeño orientado hacia la <br>
derecha. Deslizamos el retenedor hacia abajo hasta que se encuentre con la parte superior de la <br>
 Raspberry Pi.</div> <br> <br> <br>
<img src="imagenes/Imagen9.png" id="img9"> <br> <br> <br>
 <div> Insertamos el LED en el orificio central del retenedor pequeño. </div> <br> <br> <br>
<img src="imagenes/Imagen10.png" id="img10"> <br> <br> <br>
Por último, colocamos la cabeza. <br> <br> <br>
<img src="imagenes/Imagen11.png" id="img11"> <br> <br> <br>
¡Ya está listo nuestro TJBot! <br> <br> <br>
</div> <br>
<b> 1.2.1. CÓMO CONECTAR LOS COMPONENTES </b> <br> <br>
<div id="texto7">A continuación, se muestra un esquema de la conexión de los diferentes componentes electrónicos que forman parte de nuestro TJBot. <br> <br> <br>
<img src="imagenes/Imagen12.png" id="img12"> <br> <br>
</div>
 
