# Contesta a las siguientes preguntas en el README.md de este repositorio. Utiliza el lenguaje Markdown y el editor Visual Studio Code con su plugin correspondiente:
## 1. Indica qué es un lenguaje de marcas.
   
   Un lenguaje de marcas es un lenguaje que codifica un documento y su contenido a través de marcas ó etiquetas.

##  2. Características generales de los lenguajes de marcas.
Las características generales de los lenguajes de marcas son:
  
**1. USO DE TEXTO PLANO:**
  Es una ventaja porque puede ser editado con un simple editor de texto.
  
**2. COMPACIDAD:** 
 Las marcas ó etiquetas se entremezclan con el propio contenido.

**3. FACILIDAD DE PROCESAMIENTO:** 
Permite el desarrollo de lenguajes especializadas según el tipo de documento que necesitemos procesar.

**4. FLEXIBILIDAD:** Se puede combinar con otros lenguajes.  


##  3. Clasifica los lenguajes de marcas e identifica los más relevantes.  

   
**MARCADO DE PRESENTACIÓN**:
  Indica como presentar el texto de un documento. 
  
**MARCADO DE PROCESAMIENTO**:
Define la presentación y el programa que representa el documento debe interpretar las etiquetas para realizar acciones en función de ellas.

**MARCADO DESCRIPTIVO ó SEMÁNTICO**
Describe las partes en las que se estructura el documento, es decir, definen su contenido, pero sin especificar cómo deben representarse.

## 4. Indica los distintos ámbitos de aplicación de los lenguajes de marcas.

    Gráficos 2D: SVG, CGM, VML, InkML.
    Gráficos 3D: VRML/X3D, STEP.
    Matemática: MathML y OpenMath.
    Música: LilyPond y MusicXML.
    Taxonomía: DITA
    Contabilidad financiera: eXtensible Business Reporting Language.
    Geomática: Geography ML.
    Aeronáutica: Spacecraft ML.
    Multimedia: Synchronized Multimedia Integration Language.
    Voz: VoiceXML.
    Mensajería instantánea: XMPP.
    Videojuegos: BulletML, COLLADA.

## 5. Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:

1. HTML:

``` 
<html>
      <head>
      </head>
      <body>
        <p>Hola mundo!</p>
      </body>
</html>
```
Es una pagina web(`<html>`) con una **cabecera** (`<head>`) que mostrará un **título** (`<title>`) " Mi primera "página web" y el **mensaje** "Hola Mundo!" (`<body>`) cuando sea abierta por cualquier navegador (_Chrome, FireFox,Edge, etc_..)

2. iCal:
```
BEGIN:VCALENDAR
VERSION:2.0
PRODID:Cal_App//correocreador@hotmail
METHOD:PUBLISH
BEGIN:VEVENT    
UID:123456789@example.com
LOCATION:Madrid
SUMMARY:Reunión
DESCRIPTION:Reunión de Lanzamiento
CLASS:PUBLIC
DTSTART:20191101T100000Z
DTEND: 20191101T120000Z
DTSTAMP: 20191027T155954Z
END:VEVENT
END:VCALENDAR
```
Todos los archivos iCal **comienzan** con `BEGIN:VCALENDAR`. En ellos se especifica la **versión del formato** que se va a utilizar (`VERSION:2.0`), la **dirección del creador o aplicación utilizada** (`PRODID`), **cómo se transfiere** la entrada del evento(`METHOD`) y el **evento** en sí (desde `BEGIN:VEVENT` hasta `END:VEVENT`). 

Los programas de calendario típicos, que incluyen los datos basados en la web del calendario, aceptan el formato iCalendar, como

  - Google Calendar
 - Calendario de Android
 - Microsoft Outlook
 - Calendario de Blackberry
 - Calendario de macOS/iOS 
    
3. vCard

  ```
BEGIN:VCARD
VERSION:4.0
N:Gump;Forrest;;Mr.;
FN:Forrest Gump
ORG:Bubba Gump Shrimp Co.
TITLE:Shrimp Man
PHOTO;MEDIATYPE=image/gif:http://www.example.com/dir_photos/my_photo.gif
TEL;TYPE=work,voice;VALUE=uri:tel:+1-111-555-1212
TEL;TYPE=home,voice;VALUE=uri:tel:+1-404-555-1212
ADR;TYPE=WORK;PREF=1;LABEL="100 Waters Edge\nBaytown\, LA 30314\nUnited States of America":;;100 Waters Edge;Baytown;LA;30314;United States of America
ADR;TYPE=HOME;LABEL="42 Plantation St.\nBaytown\, LA 30314\nUnited States of America":;;42 Plantation St.;Baytown;LA;30314;United States of America
EMAIL:forrestgump@example.com
REV:20080424T195243Z
x-qq:21588891
END:VCARD
  ```

Todas las vCards comienzan con `BEGIN: VCARD` y terminan con `END: VCARD`. Todas las vCards deben contener la propiedad `VERSION`, que especifica la versión de la vCard. La VERSIÓN debe aparecer inmediatamente después de BEGIN, excepto en la vCard estándar 2.1, que le permite estar en cualquier parte de la vCard. Este tipo de archivo fue creado para la apliaciones de correos, pero ahora es utilizada por diversas aplicaciones, por ejemplo, cuando compartimos un contacto por whatsapps.

4. KML
```
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
   <name>Oviedo</name>
   <description>Ciudad de Oviedo, capital de Asturias</description>
   <Point>
     <coordinates>-5.843868,43.360758,0</coordinates>
   </Point>
  </Placemark>
 </kml>
 ```
Un archivo KML tiene un encabezado XML y una declaración de nombres KML. Luego tiene un objeto de marca de posición que contiene los elmentos nombre, descripción y un punto.
Un objeto de marca de posición (`<Placemark>`) que contiene los siguientes elementos:
un nombre (`<name>`) que se utiliza como etiqueta para la marca de posición,
una descripción (`<description>`) que aparece en una "viñeta" junto a la marca de posición, un punto (`<Point>`) que especifica la posición de la marca de posición en la superficie de la Tierra (la longitud, la latitud y, opcionalmente, la altitud).
Este tipo de archivo lo utilizan apliaciones ArcGis,Google Earth, Google Maps, etc... Todo software para visualizar información en un contexto geográfico.

5. RSS

```
 <?xml version="1.0" encoding="UTF-8" ?>
 <rss version="2.0">
 <channel>
  <title>Título del RSS</title>
  <description>Descripción del RSS</description>
  <link>http://www.sitiodelquesedeseapublicar.com/main.html</link>
  <lastBuildDate>Mon, 06 Jan 2013 00:01:00 +0000 </lastBuildDate>
  <pubDate>Mon, 06 Jan 2013 16:20:00 +0000 </pubDate>
  <ttl>1800</ttl>
  
  <item>
   <title>Entrada dentro del RSS</title>
   <description>Descripción de la entrada</description>
   <link>http://www.sitiodelquesedeseapublicar.com/enero-2013.html</link>
   <guid>clave única</guid>
   <pubDate>Mon, 06 Jan 2013 17:20:00 +0000 </pubDate>
  </item>
  
 </channel>
 </rss>
```
 Es un lenguaje fácilmente interpretable por humanos y software. Al igual que el anterior tipo de archivo, se ve claramente un encabezado y un cuerpo. El encabezado lo conforman típico encabezado XML (`<?xml ...>?`) y una declaración RSS (`<rss version="2.0">`) que determina la versión. El cuerpo lo componen el elemento `<channel>` y uno o varios subelementos `<item>`. Este tipo de archivos los consumen aplicaciones llamadas agregadores de rss, como FeedReader, Feedly, FlipBoard, etc..
> 
## De interés:
- [Lenguaje de Marcas tipos y clasificación de los más relevantes](http://www.docencia.taboadaleon.es/)

- [Lenguaje de marcado](www.ecured.cu)

- [Características (wikipedia)](https://es.wikipedia.org/wiki/Lenguaje_de_marcado#Caracter%C3%ADsticas)

- [Clasificación](http://mural.uv.es/)

- [Ventajas para el tratamiento de la información](http://juangualberto.github.io/lmsgi/tema01/ventajas_para_el_tratamiento_de_la_informacin.html)