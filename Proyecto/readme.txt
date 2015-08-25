Synopsis

El --- es un proyecto orientado a los estudiantes nuevos. Mediante videos se pretende ser una guia para los estudiantes de primer ingreso, asi como para los que necesiten una ayuda para orientarse por la nueva sede de la universidad.


----------------------------------------------------------------------------------------------------

Code Example
 
Este boton cambia entre las pantallas, con su texto y color establecido mediante "text" y "background_color" respectivamente, solo resta establecer la accion que ocurrira al presionarlo (on_press: root.current = "Biblioteca").
Button:
	background_color: (0.5, 1.5, 3.3, 6.5)
	text: 'Biblioteca (CRAI)'
	on_press: root.current = 'Biblioteca'

Para la reproduccion del video utilizamos el reproductor integrado de Kivy llamado "VideoPlayer".
Para poder utilizar este reproductor, primeramente, en el "main.py" (en este caso "ProyectoApp.py") se debe importar la libreria:

from kivy.uix.videoplayer import VideoPlayer

Luego se define la ruta del video mediante "source" y se estableze el estado inicial con "state" (pausado en este caso).

VideoPlayer:
	source:'biblioteca.mp4'
	state:'pause'

----------------------------------------------------------------------------------------------------

Motivacion

Como todos nosotros fuimos alguna vez estudiantes de primer ingreso, y sufrimos el estar perdido sin saber donde quedan las cosas, decidimos ayudar a los nuevos, tratando de facilitarles la adaptacion de una manera distinta.


----------------------------------------------------------------------------------------------------

API Reference

https://github.com/ProyectoUIPGrupo1/Proyecto-uip-grupo-1


----------------------------------------------------------------------------------------------------

Contributors

https://github.com/ProyectoUIPGrupo1/Proyecto-uip-grupo-1/pulse