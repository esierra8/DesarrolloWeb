Intro HTML
==========

HTML
	**HyperText Markup Language** proporciona una forma lógica de estructurar 
	contenido para páginas web.

.. Es el idioma utilizado para crear las páginas web que visita todos los días.

Un lenguaje de marcado es un lenguaje informático que define la estructura y 
presentación de los textos.

* Los elementos de HTML son los bloques de construcción de las páginas HTML.
* Los elementos de HTML se crean con etiquetas.
* Las etiquetas de HTML etiquetan partes de contenido como "encabezado", 
  "párrafo","tabla", etc.
* Los navegadores no muestran las etiquetas HTML, pero las utilizan para procesar 
  el contenido de la página

.. image:: ../img/htmlEtiqueta.png

Y con un conjunto de bloques o elementos construimos lo que es una pagina web. 
Son un conjunto de elementos como que guiaran a tu navegador a representar el 
texto de cierta forma. A continuación te voy a dar un ejemplo de la base de un 
archivo html. Es múy fácil acordarte de esto porque es similar a tu propio cuerpo. 
Con cábeza y un cuerpo. La indentación que veras a continuacion es para que tu 
codigo sea mas leible y este mas estructurado. Creeme te **ahorraras** mucho 
tiempo si simplemente empiezas a programar con una buena indentacion.

.. literalinclude:: ../code/example1.html
   :language: html
   :linenos:
   :caption: example1.html

.. important::

	**Regla #1** Cada vez que abres una etiqueta, asegurate de **SIEMPRE** cerrarla 
	como acontinuación ``<h1> </h1>``. Existen casos en que no tienes que cerrar 
	la etiqueta pero eso te lo explico mas adelante. Para dejar saber a tu  
	navegador web que estás utilizando el lenguaje HTML con el elemento 
	``<!Doctype html>``. Esta etiqueta no tienes que cerrarla.

* La declaración ``<! DOCTYPE html>`` define este documento como HTML5
* El elemento ``<html>`` es la raíz de una página HTML
* El elemento ``<head>`` contiene información meta sobre el documento
* El elemento ``<title>`` especifica un título para el documento
* El elemento ``<body>`` contiene el contenido **visible** de la página
* El elemento ``<h1>`` define un encabezado grande
* El elemento ``<p>`` define un párrafo

Elementos pueden ir adentro de otros elementos y como pueds ver en la linea 4, 
el elemento ``<title>`` esta dentro de el elemento ``<head>``. Y debido a eso 
indentamos el elemento que se encuentra dentro.

Cuando abras por primera vez *Brackets* aparecera un archivo con texto ya escrito
llamado *index.html*. Elimina todo, cópia y pega el ejemplo de *html5* que vez aquí.
Lánza tu página en Google Chrome así:

.. image:: ../img/BracketsExample1.png

Google Chrome debería abrirse con una página que luce algo así:

.. image:: ../img/GoogleChromeExample1.png

.. attention:: 
	Felicidades! Has creado tu primer página web. Te aseguro que este sera un 
	curso que te emocionara terminar. Acuerdate nadamas que la creatividad sera 
	tu unico limite. 