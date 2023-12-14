# UD2 A2 HTML semántico

HTML Semántico es el uso de las etiquetas HTML para reforzar la semántica, o el significado, de la información en las páginas web, mejor que simplemente redefinir su forma de presentación o apariencia. El HTML semántico es procesado por los navegadores. CSS se usa para definir la presentación de la página a los usuarios humanos. Es una manera de separar la presentación del contenido. *HTML5* introduce muchas *etiquetas semánticas* como *section, article, footer, progress, nav*.... **Existen ciertas etiquetas cuyo uso se desaconseja** con esta nueva filosofía del HTML semántico: 

El **elemento b** debe usarse como último recurso cuando ningún otro elemento es más apropiado. En particular,

- los _encabezados_ deben usar los elementos _h1 a h6_,
- para _indicar énfasis_ debe usar el elemento _em_,
- la _importancia_ debe indicarse con el elemento _strong_ y
- el _texto marcado o resaltado_ debe usar el elemento _mark_.

Lo mismo ocurre con la **etiqueta i**: Se anima a los autores a considerar si otros elementos podrían ser más aplicables que el elemento i, por ejemplo,

- el elemento _em_ para _marcar énfasis_, o
- el elemento _dfn_ para _marcar la instancia definitoria_ de un término.

Las _hojas de estilo CSS deberían especificar las fuentes cursiva, negritas, subrayadas, etc._ Esto es porque las cursivas son usadas para otros propósitos además de hacer énfasis, como citar una fuente. Implementa el apartado "3.3: Cuerpo del documento" donde se hace uso de las etiquetas semánticas introducidas por HTML5. Enlázalas a otro documento web también local mediante la etiqueta &lt;a> . Añade un logo con la etiqueta &lt;img>

[Respuesta](./Respuesta/respuestas.html)


De interés:

- [whatwg.org](https://html.spec.whatwg.org/#the-a-element) - The "a" element