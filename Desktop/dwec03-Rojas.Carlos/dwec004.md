# Browser devtools and JS Basics

## Introducción

### Objetivo

- Echar un vistazo al browser devtools.
- Primera aproximación práctica a JS.

### Versiones de JS

A lo que llamamos JavaScript se le llama formalmente ECMAScript y tiene
varias versiones, con posibles incompatibilidades en detalles (y en no tan
detalles).

Vamos a obviar al principio esta complejidad (fiándonos de que MDN utilice
suficientemente buenas prácticas en sus ejemplos y ejercicios).

Pero al menos, para cuando salgan colateralmente nombres de versiones,
tener en cuenta esta mínima referencia para contextualizarlas en el tiempo:

- v1, v2 y v3: desde 1997, una por año.
- v5: 2009
- V6, v7, ...: desde 2015, una por año (restar un año al número de versión)

### Comillas en JS

En JS son exactamente equivalentes las comillas dobles y las sencillas (a
diferencia de en otros lenguajes, como Java, shell script, etc). Se usa una u
otra por comodidad de no escapar cosas (comillas) que se metan entre ellas...
Cuando no hay nada que escapar, se elige un convenio, y nos ceñimos siempre a
él. Si estamos colaborando (proyecto con otros), nos ceñimos al que se esté
usando ahí.

Ver:

<https://bytearcher.com/articles/single-or-double-quotes-strings-javascript>

Las comillas sencillas son más populares (condicionado por ser más usadas en
frameworks). Más guías de estilo las recomiendan. Por otro lado, las otras son
más familiares si vienes de otros lenguajes, y JSON no permite sencillas (luego
si usamos sencillas, cuando trabajamos con JSON hay que cambiar el chip).

Los ejemplos que vemos del MDN utilizan sencillas... Nos ceñimos a ello por el
momento.

## Browser devtools

Las *browser devtools* son herramientas para desarrolladores que están
embebidas en los navegadores modernos, para facilitar la experimentación
directa, el debugging, la comprensión de código ajeno...

Seguimos el pequeño tutorial al respecto en MDN:

<https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools>

Usamos FF para que se parezca lo más posible al tutorial (habrá diferencias por
no usar su misma versión de FF).

Al seguir el primer paso, que es abrir:

<http://mdn.github.io/beginner-html-site-scripted/>

en nueva ventana, introduce tu nombre y primer apellido (particularizará la
página).

Sigue las indicaciones en directo del profesor, y captura en los momentos
solicitados la ventana del navegador mostrando los distintos elementos
relevantes que demuestran que has seguido las indicaciones:

- 01.png: Tras el recorrido por el inspector, habiendo modificado el HTML y el
  CSS según lo indicado en directo.
- 02.png: Tras el recorrido por el debugger, habiendo puesto el breakpoint
  solicitado y ejecutado hasta él.
- 03.png: Tras el uso de la consola, habiendo realizado las acciones indicadas.

## JS Basics

Seguimos ahora el tutorial:

<https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics>

En este caso, vamos a trabajar sobre Chrome.

Sigue las indicaciones en directo del profesor, y captura en los momentos
solicitados la ventana del navegador mostrando los distintos elementos
relevantes que demuestran que has seguido las indicaciones:

- 04.png: Tras el ejemplo "Hello World" sobre fichero en local, según lo
  indicado en directo. Se muestra la página y el main.js en el devtools.
- 05.png: Tras el "Language basics crash course" sobre la consola, según lo
  indicado en directo. Se muestra la página y la consola del devtools (donde
  aparecen los comandos ejecutados y sus salidas).
- 06.png: Tras el "Supercharging our example website", según lo indicado en
  directo. Se muestra la página y el main.js en el devtools.

## Entrega

  Fichero ZIP con nombre según el convenio habitual. Contiene las imágenes en
  su raíz.
