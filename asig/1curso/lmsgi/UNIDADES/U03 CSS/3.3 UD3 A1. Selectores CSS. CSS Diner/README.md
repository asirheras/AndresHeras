![CSS Diner COMPLETADO](./CSS%20Dinner.png)




  # #01. SELECTS THE PLATES! - Selector TIPO

	Selecciona los elementos por su tipo

## Respuesta:
***
## `` plate``
***
***
<br/>
<br/>
<br/>


#  #02. SELECTS THE BENTO BOXES! - Selector TIPO


    Selecciona los elementos por su tipo

## Respuesta:
***
## ``bento``
***
***
<br/>
<br/>
<br/>

# #03. SELECTS THE FANCY PLATE - Selector ID (#ID)

    Selecciona elementos con una ID
 
## Respuesta:
***
## `#fancy`
***
***
<br/>
<br/>
<br/>

# #04.SELECTS THE APPLE ON THE PLATE - Selector DESCENDIENTE (ESPACIO EN BLANCO)
***
***

	Selecciona un elemento que está dentro de otro elemento

## Respuesta:
***
## `plate apple`
***
***
<br/>
<br/>
<br/>

# #05. SELECTS THE PICKLE ON THE FANCY PLATE - Combinación del selector DESCENDIENTE y el selector ID

	Puedes combinar cualquier selector con un selector DESCENDIENTE.

## Respuesta:
***
## `#fancy pickle`
***
***
<br/>
<br/>
<br/>


# #06. SELECTS THE SMALL APPLES! - Selector de CLASE (.classname)
***
	Selecciona los elementos por su clase.

## Respuesta:
***
## `.small`
***
***
<br/>
<br/>
<br/>

# #07. SELECTS THE SMALL ORANGES! - Combinación del selector CLASE con un selector TIPO (A.classname)
***
	Se puede combinar el selector CLASE con otros selectores, como por ejemplo el selector TIPO.

## Respuesta:
***
### `orange.small`
***
***
<br/>
<br/>
<br/>

# #08. SELECTS THE SMALL ORANGES IN THE BENTOS - Combinación del selector CLASE y un selector DESCENDIENTE

	Combina los anteriores selectores que has aprendido para resolver el problema.

## Respuesta:
***
## `bento orange.small`
***
***
<br/>
<br/>
<br/>

# #09. SELECTS ALL THE PLATE AND BENTOS - Combina selectores con ","
	Puede combinar cualquier selector de esta manera y puede especificar más de dos.

## Respuesta:
***
## `plate,bento`
***
***
<br/>
<br/>
<br/>


# #10. SELECT ALL THINGS! - Selector UNIVERSAL (*)

	Selecciona todos los elementos

## Respuesta:
***
## `*`
***
***
<br/>
<br/>
<br/>

# #11. SELECT EVERYTHINGS ON A PLATE - Combinación de un selector TIPO con el selector UNIVERSAL (*)

	Combina el selector UNIVERSAL

## Respuesta:
***
## `plate *`

# #12. SELECT EVERY APPLE THAT´S NEXTO TO A PLATE - Selector de HERMANOS ADYACENTES (A+B)

	Selecciona un elemento que está al lado de otro elemento

## Respuesta:
***
## `plate + apple`
***
***
<br/>
<br/>
<br/>

# #13. SELECT THE PICKLES BESIDE THE BENTO - Selector de HERMANOS generales(A~B)

	Selecciona elementos que siguen a otro elemento.

## Respuestas:
***
## 1ª) `bento~pickle`
## 2ª) `pickle~pickle`
***
***
<br/>
<br/>
<br/>
	
# #14. SELECT THE APPLE DIRECTLY ON A PLATE - Selector HIJO(A>B)
	Selecciona el HIJO DIRECTO de un elemento

## Respuesta:
***
## `plate>apple`
***
***
<br/>
<br/>
<br/>

# #15. SELECT THE TOP ORANGE - PSEUDO-SELECTOR de PRIMER HIJO (:first-child)

	Selecciona el primer ELEMENTO HIJO DENTRO de otro elemento

## Respuestas:
***
## 1ª) `plate :first-child`
***
***
<br/>
<br/>
<br/>

# #16. SELECT THE APPLE AND THE PICKLE ON THE PLATES - PSEUDO-SELECTOR de UNICO HIJO (:only-child)
	Selecciona un elemento que es ÚNICO dentro de otro elemento.

## Respuestas:
***
## `plate :only-child`
***
***
<br/>
<br/>
<br/>

# #17. SELECT THE SMALL APPLE AND THE PICKLE - PSEUDO-SELECTOR de ULTIMO HIJO (:last-child)
	Selecciona un elemento que es ÚLTIMO dentro de otro elemento.

## Respuestas:
***
## 1ª) `fancy:last-child, pickle`
## 2ª) `.small:last-child`
***
***
<br/>
<br/>
<br/>

# #18. SELECT THE 3RD PLATE - Pseudo-selector de ENÉSIMO(nth) HIJO (:nth-child(n))
	Selecciona un elemento por su orden en otro elemento, es decir, nos permite seleccionar elementos hijos (child) 
	basándonos en la posición (nth) que tengan dentro de su padre (parent).
## Respuestas:
***
## plate:nth-child(3)
***
***
<br/>
<br/>
<br/>
# #19. SELECT THE 1ST BENTO - PSEUDO-SELECTOR de ENESIMO ULTIMO HIJO (:nth-last-child(n))
	Selecciona un elemento que es ÚLTIMO dentro de otro elemento,pero contando desde el final.

## Respuestas:
***
## `bento:nth-last-child(3)`
***
***
<br/>
<br/>
<br/>

# #20. SELECT 1ST APPLE - Selector de PRIMER TIPO (:first-of-type)
	Selecciona el primer elemento de un tipo específico.

## Respuestas:
***
## `apple:first-of-type`
***
***
<br/>
<br/>
<br/>

# #21. SELECT ALL EVEN PLATES - Selector de TIPO DE ORDEN (:nth-of-type(A))
	Selecciona especificamente elementos basandose en su tipo y en el orden en que están con otro elemento ó 
	si son pares (even) ó impares(odd).

## Respuestas:
***
## `plate:nth-of-type(even)`
***
***
<br/>
<br/>
<br/>

# #22. SELECT EVERY 2ND PLATE, STARTING FROM THE 3RD - Selector de TIPO ENESIMO CON FÓRMULA (:nth-of-type(An+B))    	Selecciona cada enésimo elemento, comenzando a contar respecto a un elemento en específico
## Respuestas:
***
## `plate:nth-of-type(2n+3)`
***
***
<br/>
<br/>
<br/>


# #23. SELECT THE APPLE ON THE MIDDLE PLATE - Selector de TIPO ÚNICO (:only-of-type)
-------------------------------------------------------------------------------------------------
	Selecciona los elementos que son únicos en su tipo dentro de sus elementos padres. 

## Respuestas:
***
## `apple:only-of-type`
***
***
<br/>
<br/>
<br/>
# #24. SELECT THE LAST APPLE AND ORANGE - Selector de TIPO ULTIMO(:last-of-type)
-------------------------------------------------------------------------------------------------
	Selecciona el último elemento de un tipo específico.

## Respuestas:
***
## 1ª)`.small:last-of-type`
## 2ª)`apple:last-of-type,orange:last-of-type`


# #25. SELECT THE EMPTY BENTOS - Selector VACÍO(:empty)
-------------------------------------------------------------------------------------------------
	Selecciona los elementos que no tienene hijos.

## Respuestas:
***
## `bentos:empty`
***
***
<br/>
<br/>
<br/>

# #26. SELECT THE BIG APPLES - Pseudo-clase de NEGACIÓN (:not(X))
-------------------------------------------------------------------------------------------------
	Selecciona todos los elementos que no coinciden con la negación del selector.

## Respuestas:
***
## `apple:not(.small)`
***
***
<br/>
<br/>
<br/>

# #27. SELECT THE ITEMS FOR SOMEONE - Selector de ATRIBUTOS (A[attribute])
-------------------------------------------------------------------------------------------------
	Selecciona todos los elementos que tienen un atributo en específico.

## Respuestas:
***
## `*[for]`
***
***
<br/>
<br/>
<br/>

# #28. SELECT THE PLATES FOR SOMEONE - Selector de ATRIBUTOS (A[attribute])
-------------------------------------------------------------------------------------------------
	Selecciona todos los elementos que tienen un atributo en específico.

## Respuesta:
***
## `plate[for]`
***
***
<br/>
<br/>
<br/>


# #29.SELECT VITALY´S MEAL - Selector de VALOR DE ATRIBUTO ([attribute="value"])
-------------------------------------------------------------------------------------------------
	Selecciona todos los elementos que tienen un atributo en específico.

## Respuesta:
***
## `bento[for="Vitaly"]`
***
***
<br/>
<br/>
<br/>


# #30. SELECT THE ITEMS FOR NAMES THAT START WITH 'Sa' - Selector de ATRIBUTO que aca ([attribute^="value"])
-------------------------------------------------------------------------------------------------
	Selecciona todos los elementos que tienen un atributo que comienzan por un/os carácteres en específico.

## Respuesta:
## ``*[for^="Sa"]``
***
***
<br/>
<br/>
<br/>


# #31. SELECT THE ITEMS FOR NAMES THAT END WITH 'ato' - Selector de ATRIBUTO que termina en un valor -  ([attribute$="value"])

	Selecciona todos los elementos que tienen un atributo que acaban por un/os carácteres en específico.

## Respuestas:

## `*[for$="ato"]`


# #32. SELECT THE MEALS FOR NAMES THAT CONTAIN 'obb' - Selector de ATRIBUTO que termina en un valor -  ([attribute*="value"])
	Selecciona todos los elementos que tienen un atributo que contienea un/os carácteres en específico.

## Respuestas:
## `bento[for*="obb"]`
***
***
<br/>
<br/>
<br/>