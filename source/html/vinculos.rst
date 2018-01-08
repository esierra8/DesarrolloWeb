Vinculos o Links
================
Los vinculos se encuentran en casi todas las páginas web. Los vinculos te permiten
navegar atravez de las páginas web con facilidad. Cuando pasas el mouse por el
vinculo HTML la flecha se convierte en una mano, y cuando das click en un vinculo
navegas a otro documento HTML.

.. note::
  Los vinculos no necesariamente son textos, tambien pueden ser imagenes ú otros
  elementos de HTML.

En HTML los vinculos se definen con etiqueta ``<a>`` y se cierran con una etiqueta ``</a>``

.. code-block:: html
	:linenos:

	<a href = "url"> vinculo en texto </a>

Ejemplo
^^^^^^^
.. code-block:: html
	:linenos:

	<a href = "http://desarrollo-web.readthedocs.io"> Ejemplo </a>

El atributo ``href`` especifica el lugar de el vinculo (http://desarrollo-web.readthedocs.io)
El texto ``Ejemplo`` es el vinculo visible donde darias click. Dando click en el
texto te llevaria al vinculo.

Vinculo local
-------------
El ejemplo de arriba es un vinculo absoluto o completo, que te llevaria a una
página afuera de la que estas navegando, pero existen vinculos locales que es
un vinculo en la misma página que estas navegando y se especifica sin ``http://www...``

Ejemplo
^^^^^^^




  HTML Links - The target Attribute

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

    _blank - Opens the linked document in a new window or tab
    _self - Opens the linked document in the same window/tab as it was clicked (this is default)
    _parent - Opens the linked document in the parent frame
    _top - Opens the linked document in the full body of the window
    framename - Opens the linked document in a named frame



    HTML Links - Image as Link

    It is common to use images as links:




    HTML Links - Create a Bookmark

HTML bookmarks are used to allow readers to jump to specific parts of a Web page.

Bookmarks can be useful if your webpage is very long.

To make a bookmark, you must first create the bookmark, and then add a link to it.

When the link is clicked, the page will scroll to the location with the bookmark.
