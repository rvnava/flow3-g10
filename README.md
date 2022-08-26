# flow3-g10
Tercer ejercicio con Node-RED del diplomado Internet de las Cosas de [Código IoT](https://edu.codigoiot.com/)

## Introducción
Este segundo flujo realizado con [Node-RED](https://nodered.org/), el cual consiste agregar el nodo "text", conectarlo al nodo "function" para que los mensajes de la fecha se presenten en un formato legible en una interfaz de usuario.

Para esta práctica se usarán los siguientes nodos:

 - inject. Se usa la propiedad msg.payload de tipo timestamp y se hace recursivo cada segundo
 - function. Se usa darle formato al mensaje enviado por el nodo inject
 - debug. Se usa para visualizar las acciones del nodo inject.


## Material necesario

 - Sofware
	 - Equipo o Máquina virtual con [Ubuntu](https://ubuntu.com/) con una versión mínima 20.04
	 - [Node-RED](https://nodered.org/) (notas para [instalación](https://github.com/nodesource/distributions/blob/master/README.md))
	 - [Git](https://git-scm.com/) (notas para [instalación](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git))
 - Hardware
	 - PC o LapTop con Linux, Windows
	 - Mínimo 8 Gb en RAM
	 - Disco duro con mínimo 100 Gb de espacio libre

## Material de referencia

 - [Node-Red](https://nodered.org/)
 - [Git](https://git-scm.com/)

## Instrucciones

 - Previos
	 - Tener instalado el sofware necesario listado en el apartado **Material necesario**
	 - El programa "node-red" debe estár ejecución
	 - Tener la aplicación de Node-RED abierta en un navegador con la dirección "http://localhost:1880"
 - Ejecución
	 - Se arrastra el nodo **inject** de la barra de nodos al área de trabajo y se configura la propiedad msg.payload de tipo timestamp y se hace recursivo cada segundo
	 - Se arrastra el nodo **function** de la barra de nodos al área de trabajo, se hace doble clic sobre este nodo y se pega el siguiente código 
	 - Se arrastra el nodo **debug** de la barra de nodos al área de trabajo
	 - Se conecta el nodo **inject** con el nodo **debug**
	 - Se oprime el botón **Deploy** ubicado en la parte superior derecha

## Resultados

Los resultados de la ejecución se pueden visualizar en la barra ubicada en la parte derecha en la pestaña **debug** en el cual se mostrará un mensaje con un número cada segundo

## Evidencias

 - [Repositorio en GitHub](https://github.com/rvnava/flow1-g10.git)
 - Video en youtube 
	 - No disponible
 - blogs
	 - No disponible
 - Foros
	- No disponible
 - Redes sociales
	- No disponible
	- 
## Créditos
 
 - [LinkedIn](www.linkedin.com/in/raúl-vargas-nava-aa646925)

