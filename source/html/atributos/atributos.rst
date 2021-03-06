Atributos
=========
Atributos HTML
	Se utilizan para definir las características de un *elemento* HTML y se coloca
	dentro de la etiqueta principal del elemento. Los atributos proporcionan 
	información adicional sobre un elemento.

* Todos los *elementos* HTML pueden tener atributos.
* Los *atributos* siempre se especifican en la etiqueta principal.
* Los *atributos* usualmente vienen en un formato de nombre/valor com por 
  ejemplo: ``nombre = "valor"``

Nuestro primer ejemplo de atributos es uno muy importante, especialmente para 
las personas que no usaran el idioma de ingles en su página. 

.. literalinclude:: ../code/example2.html
   :language: html
   :emphasize-lines: 2
   :linenos:
   :caption: example2.html

.. tip:: 
	Como pueden ver, la linea subrayada tiene un cambio a nuestro ejemplo de la 
	lección pasada. 
	``<html lang="es">``
	es un atributo y define el lenguaje para el elemento html.

.. image:: ../img/AtributeExample.png

Existen muchos atributos que puedes para diferentes elementos.

* Todos los elementos tienen atributos.
* Elementos tienen sus propios atributos para ser utilizados.
* **No todos** los atributos pueden ser utilizados con todos los elementos.
* HTML no distingue entre mayusculas y minusculas. Pero **USA** minusculas, es 
  buena practica.
* Puedes usar comillas simples o dobles. Las comillas dobles son mas usadas.

Esto es el mismo ejemplo que hemos usado hasta ahorita pero lo llenare de atributos 
para que te des una mejor idea.

.. literalinclude:: ../code/example3.html
	:language: html
	:linenos:
	:caption: ejemplo3.html


``<h1 id="primerTitulo" title="Soy un encabezado"> Tu encabezado </h1>``
Nuestra primera etiqueta``<h1>`` tiene el atributo *id* que proporciona con una 
identificación y *title* proporciona un titulo que cuando pasas tu mouse por el 
encabezado te sale una linea amarillenta con tu titulo asi:

.. image:: ../img/titleExample.png

``<p id="primerParrafo" >Tu parrafo</p>``
De nuevo vemos el atributo id que identifica, en esta ocación a el parrafo.

``<a href="http://desarrolloweb.readthedocs.io/en/latest/">Da click aqui para 
navegar a readthedocs.org </a>``
Aqui vemos un nuevo elemento ``<a></a>`` este elemento es usado para los 
hipervinculos o *links*, el hipervinculo que quieres navegar se declara en el 
atributo *href*.

``<img alt="" src="w3schools.jpg" width="104" height="142">``
Otro nuevo elemento es el de ``<img>`` como puedes ver este elemento 
**no necesita** etiqueta final ``</img>``. Este elemento implementa la imagen 
que tu indiques en el atributo ``src=""``. Puedes declarar lo alto de tu imagen 
con el atributo *height="142"* y lo ancho con *width="104"* que en este caso el 
tamaño de tu imagen seria 142 pixeles de alto x 104 pixeles de largo.

**Tranquilo**
+++++++++++++
Te explicare mas en detalle estos nuevos elementos lo importante de 
esta leccion es que entiendas que existen atributos que se declaran en los 
elementos. Estos atributos dan mas información acerca de los elementos pero no 
los puedes ver en la página porque esa es información para tu navegador no para 
el usuario.



