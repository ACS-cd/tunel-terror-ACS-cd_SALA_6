# Sala 6 · LA PUERTA FINAL (HTML)

**Autor/a:** Angela Colorado Sousa - ACS-cd


## La historia
Ya has llegado al final del reto, tras incontables terrores, el grupo se encuentra delante de la prueba que les separa del mundo exterior. Una gran puerta de madera, pesada, antigua y que aún acoge multitud de arañazos de aquellos que no supieron escapar.
¿Sereís vosotros los siguientes en la lista?

## La pista
Qué pista damos y dónde está escondida.


## Diario de investigación

### Reto 1 · La voz del narrador
- **Pregunta:** ¿strong o b para la palabra que asusta? Strong.
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/strong)
- **Lo que dice (con mis palabras):** Strong marca el elemento importante del texto, dándole énfasis.
- **Prueba en pruebas.html:**   Se ve igual que usando bold.
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

### Reto 2 · ...

- **Pregunta:** ¿Qué diferencia hay entre marcar una palabra como importante y ponerla en negrita sin más? ¿Y entre dar énfasis y poner cursiva?
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/strong)
- **Lo que dice (con mis palabras):** 
- **Prueba en pruebas.html:**   
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

- **Pregunta:** ¿Con qué etiqueta indicas que algo se borró, una aclaración en letra pequeña, un superíndice o un subíndice? Del para borrar/tachar. Small para letra pequeña. Sup para superíndices.
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/del) [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/small) [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/sup) [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/sub)
- **Lo que dice (con mis palabras):**  Del marca zonas del texto que se han tachado y/o borrado. Small cambia el tamaño de fuente a uno más pequeño. Sup hace que una oparte del texto se enseñe más alto y pequeño que el resto.
Sub hace lo contrario que sub, muestra un texto pequeño y más bajo que el resto.
- **Prueba en pruebas.html:**   
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

- **Pregunta:** ¿Cómo consigues que una palabra explique su significado al pasar el ratón por encima? abbr
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/abbr)
- **Lo que dice (con mis palabras):** Abrevia el texto haciendo que se muestre sólo cuando el ratón esté encima.
- **Prueba en pruebas.html:**   
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

- **Pregunta:** ¿Para qué sirve un comentario si el visitante no lo ve? Para ayudar al programador.
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/CSS/Guides/Syntax/Comments)
- **Lo que dice (con mis palabras):** Notas explicativas para quién desarrolla el programa, no se muestran en el resultado final.
- **Prueba en pruebas.html:**   
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

### Reto 4
- **Pregunta:** ¿Cuándo debe ser una lista ordenada y cuándo no?
Cuándo una lista no necesita numeración o está dentro de otra, son sin order. Para todo lo demás, ordenadas.
¿En qué punto exacto se escribe la lista de dentro para que el validador no dé error? Hay que hacer la lista secundaria dentro de un li para que el validador no de problemas.
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/ol) [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/ul)
- **Lo que dice (con mis palabras):** Ol crea listas que se ordenan y numerizan de forma automática, mientras que ul son listas sin numeración automática u orden.
- **Prueba en pruebas.html:** Ol no necesita numeración alguna. Ul si, en caso de necesitar una forma de órden no numérica. Se necesita poner la lista secundaria dentro de su propio li.
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

**Ninguna decisión se explica más allá porque la propia pregunta anterior lo ofrece, ademas esta sala ha sido desarrollada por una persona. Así que decisiones a conjunto no ha habido ninguna**

### Reto 5
- **Pregunta:** ¿Para qué sirve el texto alternativo si la imagen ya se ve? ¿Quién lo usa? Para saber qué es la imagen si no se puede leer. Lo usan las personas con dificultades visuales altas, ej: ciegos.
¿Qué pasa si la ruta de la imagen está mal? Que la imagen aparece como rota y no se ve.
¿Qué aporta agrupar la imagen y su pie de foto frente a poner un párrafo debajo? Que salen con el mismo formato y son fáciles de identificar como unidad en el código para el programador.
¿Por qué el ancho se escribe sin unidades?
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/img)
[text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/figure)
- **Lo que dice (con mis palabras):** Las imágenes no siempre salen en la página web y el texto alternativo describe lo faltante.
Figure es contenido que lleva un título agrupado a ello, es independiente al resto de párrafos y se pueden mover sin afectar al resto de la estructura.
- **Prueba en pruebas.html:** 
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

### Reto 6
- **Pregunta:** ¿Qué partes del esqueleto del paso 1 se repiten en cualquier página? ¿Cuáles cambian? La parte que contiene los metadatos, header y los comentarios.
¿Cómo enlazas la misma hoja de estilos desde una segunda página? Colocando el nombre concreto que se ha estipulado en la hoja css.
¿Qué es un atributo global como class y para qué lo usa la hoja de estilos? Es una etiqueta que se puede añadir para dar determinadas características- La hoja de estilos lo usa para determinar qué parte va en un estilo u otro.
- **Fuente:** enlace a MDN o a la especificación [text](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Global_attributes)
- **Lo que dice (con mis palabras):**  Soon características que se pueden añadir a los elementos para diferenciarlos de otros o sólo aplicar un estado específico al que contenga la etiqueta concreta.
- **Prueba en pruebas.html:** 
- **Decisión en mi sala:** uso ... en "..." porque ...
- **Pista de nivel usada:** ninguna

## Captura
![Mi sala](docs/captura.png)

## Créditos
Imágenes y sonidos con autor, web y licencia.