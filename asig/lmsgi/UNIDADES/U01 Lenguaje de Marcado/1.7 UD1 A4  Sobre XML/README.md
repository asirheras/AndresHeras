#  UD1 A4 Sobre XML

## Contesta a las siguientes preguntas en el README.md de este repositorio. Utiliza el lenguaje Markdown y el editor Visual Studio Code con su plugin correspondiente:

### 1. Indica las características propias del lenguaje XML.
*  **EXTENSIBLE**:no es un lenguaje predefinido, es decir, la etiquetas no está predefinidas, si no que al contrario, se pueden definir nuevas etiquetas.
*  **VERSATIL** porque separa contenido, estructura y presentación. Esta carácteristicas es fundamental, porque permite Esto le permite permite exportar los datos contenidos a otros formatos ( como por ejemplo HTML, PDF, RTF y otros), además, de 
*  **ESTRUCTURADO** porque se pueden modelar datos a cualquier nivel de complejidad
*  **VALIDABLE**, cada documento se puede validar frente a un DTD/Schema
*  **ABIERTO**: _independiente_ de empresas,sistemas operativos,lenguajes de programación o entornos de desarrollo.
*  **SENCILLO**, fácil de aprender y de usar.

    
### 2. Identifica la estructura de un documento XML y sus reglas sintácticas.
Un documento XML está formado por dos partes:
* **Prólogo**: Está al principio del documento y es opcional. Proporciona información sobre el propio documento y está formado por:

    * **Definición XML.** 
Determina la versión XML, codificación y si la validez del documento depende de otro documento externo. Empieza con los caracteres &quot;&lt;?&quot; y termina con &quot;?&gt;&quot; como  las instrucciones de procesamiento pero no lo es. Aunque el prólogo es opcional, si se escribe la definición XML, debe estar obligatoriamente acompañado por el atributo _versión_, y opcionalmente, los atributos _encoding_ (con su valor por defecto, UTF-8) y _standalone_ (con su valor por defecto, no), y en este estricto orden. El **atributo encoding** especifica el **juego de carácteres del documento** y **atributo standalone** la **dependencia o no con otros documentos**. Ejemplo 
  
        ```
        <?xml ?>
        <?xml versión= “1.0” ?>
        <?xml versión= “1.0” encoding=”utf-8” ?>
        <?xml versión= “1.0” encoding=”utf-8” standalone=”yes” ?>
        ```

* **Cuerpo, Ejemplar ó etiqueta raíz**: Es la parte que contiene realmente el documento XML. Está formado por un conjunto de elementos XML organizados en una estructura estructura jerárquica, cuyo nodo raíz es el ejemplar. 
### 3. En XML qué es un nodo raíz

En un documento XML siempre tiene que haber un elemento padre del que descienden el resto de elementos como una estructura de árbol.
### 4. Indica qué es un elemento vacío. Ejemplos

Es un elemento que no contiene ningún valor, por ejemplo

```
<telefono></telefono> 
```
ó se puede escribir como una única etiqueta especial (etiqueta de _elemento vacío_), formada por el carácter “<”, el nombre del elemento, y la cadena “/>”, como vemos el siguiente ejemplo:
```
<telefono/>
```


### 5. Qué sentido tiene crear documentos XML bien formado.

Sí porque de esta manera si puede ser procesado  sin inconvenientes ni problemas de compatibilidad por múltiples sistemas.

### 6. Qué es un espacio de nombres. Ventajas de uso.
Un espacio de nombres XML es un conjunto de nombres o vocabulario, identificados por una referencia URI (_identificador uniforme de recurso_), que se utilizan en documentos XML como tipos de elemento y nombres de atributo.

Para definir un espacio de nombres al que pertenece un elemento se usa, dentro de la etiqueta de inicio de ese elemento, el atributo XML reservado “xmlns”, cuyo valor debe ser su URI (nombre del espacio de nombres). El formato genérico de una declaración de un espacio de nombres es el siguiente:
```

    xmlns(:<prefijo>)?=<nombre_del_espacio_de_nombres(URI)>
```
El prefijo, que es opcional, es un alias que identifica al espacio de nombres. El **prefijo** de un espacio de nombres es **totalmente arbitrario**; lo que define e identifica un espacio de nombres es, en realidad, el URI. Hay que destacar que el URI no se interpreta realmente como una dirección; se trata como una cadena de texto por el analizador XML. Por ejemplo:
```
    xmlns:xhtml="http://www.w3.org/1999/xhtml
```
El hecho de usar un URI como identificador del espacio de nombres es un artificio para garantizar, que no se reutilizará de forma accidental el mismo identificador para dos vocabularios diferentes.
El uso de un espacio de nombres no implica que la definción del vocabulario exista realmente, ni sirve para localizar la definición en el caso de que exista. Para ello se debe emplear la declaración DOCTYPE.


***
## De interés:

* [abrirlallave - XML](https://www.abrirllave.com/xml/)

* [abrirlallave - Espacios de Nombres](https://www.abrirllave.com/xml/espacios-de-nombres.php)

* [abrirlallave - Instrucciones de Procesamiento](https://www.abrirllave.com/xml/instrucciones-de-procesamiento.php)


* [abrirlallave - Referencia a Entidades](https://www.abrirllave.com/xml/referencias-a-entidades.php)

* [abrirlallave - Referencia de caracteres ](https://www.abrirllave.com/xml/referencias-de-caracteres.php)

* [abrirlallave -Comentarios](https://www.abrirllave.com/xml/comentarios.php)
