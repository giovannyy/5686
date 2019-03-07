
Entonces, ¿qué es HTML en realidad?Sección
 

HTML no es un lenguaje de programación; es un lenguaje de marcado que define la estructura de tu contenido. HTML consiste en una serie de elementos que usarás para encerrar diferentes partes del contenido para que se vean o comporten de una determinada manera. Las etiquetas de encierre pueden hacer de una palabra o una imagen un hipervínculo a otro sitio, se pueden cambiar palabras a cursiva, agrandar o achicar la letra, etc. Por ejemplo, tomemos la siguiente línea de contenido:

 

Mi gato es muy gruñon
Si queremos especificar que se trata de un párrafo, podríamos encerrar el texto con la etiqueta de párrafo  (<p>) :

<p>Mi gato es muy gruñon</p>
Anatomía de un elemento HTMLSección
Exploremos este párrafo en mayor profundidad.

elementos de gato gruñon

Las partes principales de nuestro elemento son:

La etiqueta de apertura: consiste en el nombre del elemento (en este caso, p), encerrado por paréntesis angulares (< >) de apertura y cierre. Establece dónde comienza o empieza a tener efecto el elemento — en este caso, dónde es el comienzo del párrafo.
La etiqueta de cierre: es igual que la etiqueta de apertura, excepto que incluye una barra de cierre (/) antes del nombre de la etiqueta. Establece dónde termina el elemento — en este caso dónde termina el párrafo.
El contenido: este es el contenido del elemento, que en este caso es sólo texto.
El elemento: la etiqueta de apertura, más la etiqueta de cierre, más el contenido equivale al elemento.
Los elementos pueden también tener atributos, que se ven así:

atributo html

Los atributos contienen información adicional acerca del elemento, la cual no quieres que aparezca en el contenido real del elemento. En este caso, el atributo class permite darle al elemento un nombre identificativo, que puede ser usado luego para apuntarle al elemento información de estilo y demás cosas.

Un atributo debe tener siempre:

Un espacio entre éste y el nombre del elemento (o del atributo previo, si el elemento ya posee uno o más atributos).
El nombre del atributo, seguido por un signo de igual (=).
Comillas de apertura y de cierre, encerrando el valor del atributo.
Anidando elementosSección
Puedes también colocar elementos dentro de otros elementos  — esto se llama anidamiento. Si, por ejemplo, queremos resaltar una palabra del texto (en nuestro ejemplo la palabra "muy"), podemos encerrarla en un elemento <strong>, que significa que dicha palabra debe ser enfatizada:

<p>Mi gato es <strong>muy</strong> gruñon.</p>
Debes asegurarte que los elementos estén correctamente anidados: en el ejemplo de abajo, creamos la etiqueta de apertura del elemento <p> primero, luego la de <strong>, por lo tanto, debemos cerrar ésta etiqueta primero, y luego la de <p>. Esto es incorrecto:

<p>Mi gato es <strong>muy gruñon.</p></strong>

haaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
