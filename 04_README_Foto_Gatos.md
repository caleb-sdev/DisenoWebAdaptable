Paso 1
En este taller, continuarás trabajando con elementos HTML básicos como títulos, párrafos y listas, construyendo una aplicación de fotos de gatos.

Comienza el taller agregando un elemento h1 con el texto de CatPhotoApp.

Paso 2
Debajo del elemento h1, añade un elemento h2 con este texto:

Cat Photos

Paso 3
Crea un elemento p debajo de tu elemento h2 y dale el siguiente texto:

Everyone loves cute cats online!

Paso 4
Los comentarios te permiten dejar mensajes sin afectar la visualización en el navegador. También te permiten desactivar código. Un comentario en HTML comienza con <!--, contiene cualquier número de líneas de texto y termina con -->.

Aquí tienes un ejemplo de un comentario con el texto TODO: Remove h1:

Código de ejemplo
<!-- TODO: Remove h1 -->
Añade un comentario sobre el elemento p con este texto:

TODO: Add link to cat photos

Paso 5
HTML5 tiene diferentes elementos que ayudan a diferenciar diferentes tipos de contenido. Estos elementos hacen tu código HTML más fácil de leer y ayudan con el Posicionamiento en buscadores (Search Engine Optimization - SEO) y accesibilidad.

El elemento main se utiliza para representar el contenido principal del cuerpo de un documento HTML. El contenido dentro del elemento main debe ser único para el documento y no debe repetirse en otras partes del documento.

Código de ejemplo
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
Identifica la sección principal de esta página agregando una etiqueta de apertura <main> antes del elemento h1, y una etiqueta de cierre </main> después del elemento p.

aso 6
En el paso anterior, has colocado los elementos h1, h2, comentario y p dentro del elemento main. Esto se llama anidamiento. Los elementos anidados deben colocarse dos espacios más a la derecha del elemento en el que están anidados. Este espacio se llama sangría (indentación en programación) y se utiliza para facilitar la lectura de HTML.

Aquí tienes un ejemplo de anidación y sangría:

Código de ejemplo
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
El elemento h1, el elemento h2 y el comentario están indentados dos espacios más que el elemento main en el código de abajo. Usa la barra espaciadora en tu teclado para agregar dos espacios más delante del elemento p para que también esté indentado correctamente.

Paso 7
Puedes agregar imágenes a tu sitio web usando el elemento img. Los elementos img tienen una etiqueta de apertura sin una etiqueta de cierre. Un elemento sin etiqueta de cierre se conoce como elemento vacío.

Agregue un elemento img debajo del elemento p. En este punto, ninguna imagen aparecerá en el navegador.

Paso 8
Los atributos HTML son palabras especiales usadas dentro de la etiqueta de apertura de un elemento para controlar el comportamiento del elemento. El atributo src en un elemento img especifica la URL (donde se localiza la imagen).

Aquí hay un ejemplo de un elemento img con un atributo src apuntando al logo de freeCodeCamp:

Código de ejemplo
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
Dentro del elemento img existente, agrega un atributo src con esta URL:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg

Paso 9
Todos los elementos img deben tener un atributo alt. El texto del atributo alt es utilizado por lectores de pantalla para mejora la accesibilidad y es mostrado en caso de que la imagen falle en cargar.

Aquí tienes un ejemplo de un elemento img con un atributo alt:

Código de ejemplo
<img src="cat.jpg" alt="A cat">
Dentro del elemento img, añade un atributo alt con este texto:

A cute orange cat lying on its back

Paso 10
Puedes hacer un enlace que te llevará a otra página con el elemento anchor (a).

Aquí hay un ejemplo que enlaza a https://www.freecodecamp.org:

Código de ejemplo
<a href="https://www.freecodecamp.org"></a>
Agrega un elemento anchor después del párrafo que te lleve a https://freecatphotoapp.com. En este punto, el enlace no aparecerá en la vista previa.

Paso 11
El texto de un enlace debe colocarse entre la etiqueta de apertura y la etiqueta de cierre de un elemento anchor (a).

Aquí hay un ejemplo de un enlace con el texto click here to go to freeCodeCamp.org:

Código de ejemplo
<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
Añade el texto cat photos al elemento anchor. Esto se convertirá en el texto del enlace.

Paso 12
Agrega las palabras See more  antes del elemento anchor y  in our gallery después del elemento anchor.

Paso 13
Agrega etiquetas p para convertir See more <a href="https://freecatphotoapp.com">cat photos</a> in our gallery. en un párrafo.

Paso 14
Convierte el texto existente cute cats en un elemento de anclaje que enlaza a:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg

Paso 15
Para abrir enlaces en una pestaña nueva, puedes usar el atributo target en el elemento ancla (a).

El atributo target especifica dónde abrir el documento vinculado. target="_blank" abre el documento vinculado en una nueva pestaña o ventana.

Aquí está la sintaxis básica para un elemento a con un atributo target:

Código de ejemplo
<a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>
Agrega un atributo target con el valor _blank al elemento ancla (a) de cat photos en la etiqueta de apertura, para que el enlace se abra en una nueva pestaña.

Paso 16
Ahora que has añadido el enlace, puedes quitar el comentario.

Paso 17
En pasos anteriores, usaste un elemento de anclaje para convertir texto en un enlace. Otros tipos de contenido también se pueden convertir en un enlace envolviéndolos en etiquetas anchor.

Aquí hay un ejemplo de cómo convertir una imagen en un enlace:

Código de ejemplo
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
Convierte la imagen en un enlace rodeándola con las etiquetas correctas. Utiliza https://freecatphotoapp.com como valor del atributo href del elemento archor.

Paso 18
Antes de añadir nuevo contenido, deberías utilizar un elemento section, para separar el contenido de cat photos, del contenido que añadiremos después.

El elemento section se utiliza para definir secciones en un documento, como capítulos, encabezados, pies de página o cualquier otra sección del documento. Es un elemento semántico que ayuda con el SEO y la accesibilidad.

Código de ejemplo
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
Toma tu elemento h2, dos elementos p y el elemento de ancla (a) y anídalos en un elemento section.

Paso 19
Es hora de añadir una nueva sección con un elemento section. Añade un segundo elemento section debajo del elemento section existente.

Paso 20
Dentro del segundo elemento section, añade un nuevo elemento h2 con el texto Cat Lists.

Paso 21
Cuando agregas un elemento de encabezado de menor rango a la página, se implica que estás comenzando una nueva subsección.

Después del último elemento h2 del segundo elemento section, agrega un elemento h3 con este texto:

Things cats love:

Paso 22
Para crear una lista no ordenada de elementos, puedes usar el elemento ul.

Después del elemento h3 con el texto Things cats love:, añade una lista desordenada, unordered list - (ul). Ten en cuenta que nada será mostrado aún.

Paso 23
El elemento li es usado para crear una lista de elementos en una lista ordenada o en una lista desordenada.

Aquí hay un ejemplo de una lista de objetos en una lista desordenada:

Código de ejemplo
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
Dentro del elemento ul anida tres elementos li para mostrar tres cosas que aman los gatos:

catnip

laser pointers

lasagna

Paso 24
Después de la lista no ordenada, agrega una imagen nueva con un valor de atributo src:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg

Y su valor de atributo alt a:

A slice of lasagna on a plate.

Paso 25
El elemento figure representa contenido independiente y te permitirá asociar una imagen a una descripción.

Introduce la imagen que acabas de añadir dentro de un elemento figure.

Paso 26
Un elemento (figcaption), se utiliza para añadir una descripción o leyenda para describir una imagen anidada en un elemento figure.

Aquí tienes un ejemplo de un elemento figcaption con la leyenda de A cute cat:

Código de ejemplo
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
Después de anidar la imagen en el elemento figure, añade un elemento figcaption con el texto:

Cats love lasagna.

aso 27
Para poner énfasis en una palabra o frase específica, puedes utilizar el elemento em.

Enfatiza la palabra love en el elemento figcaption envolviendola en un elemento énfasis em.

Paso 28
Después del elemento figure, añade un elemento h3 con el texto:

Top 3 things cats hate:

Paso 29
El código de una lista ordenada, ordered list (ol), es similar al de una lista no ordenada, unordered list (ul), pero los elemento de una lista ordenada aparecen enumerados.

Debajo del elemento h3, agrega una lista ordenada con estos tres elementos de lista:

flea treatment thunder other cats

Paso 30
Después de la lista ordenada (ol), añade otro elemento figure.

Paso 31
Dentro del elemento figure que acabas de añadir, anida un elemento img con un atributo src con el valor https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg.

Paso 32
Para mejorar la accesibilidad de la imagen que agregaste, añade un atributo alt con el texto:

Two tabby kittens sleeping together on a couch.

Paso 33
Después del último elemento img añade un elemento figcaption con el texto Cats hate other cats.

Paso 34
El elemento strong se utiliza para indicar que una parte de un texto es importante o urgente.

En el figcaption que acabas de añadir, indica que hate tiene una fuerte importancia envolviéndolo en un elemento strong.

Paso 35
El elemento footer se usa para definir el pie de página de un documento o sección. Un pie de página normalmente contiene información sobre el autor del documento, datos de copyright, enlaces a términos de uso, información de contacto, etcétera.

Después del elemento main, añade un elemento footer.

Paso 36
Anida un elemento p con el texto No Copyright - freeCodeCamp.org dentro del elemento footer.

Paso 37
Convierte el texto existente freeCodeCamp.org a un link, poniéndolo dentro de un elemento anchor (a). El valor del atributo href debe ser https://www.freecodecamp.org.

Paso 38
Puedes notar que todo lo que has añadido hasta ahora, está dentro del elemento body. Todos los elementos que deben ser renderizados o mostrados en la página, deben ir dentro del elemento body. Sin embargo, otro tipo información que también es importante va dentro del elemento head.

El elemento head se usa para contener metadatos sobre el documento, como su título, enlaces a hojas de estilo y scripts. Los metadatos son información sobre la página que no se muestra directamente en la página.

Agregue un elemento head sobre el elemento body.

Paso 39
El elemento title (título) determina lo que los navegadores muestran en la barra de título o en las pestañas del navegador.

Agrega un elemento title dentro del elemento head usando el texto a continuación:

CatPhotoApp

Paso 40
Puedes ver que todo el contenido de la página está anidado dentro de un elemento html. El elemento html es elemento esencial de una página HTML y envuelve todo el contenido en la página.

También puedes especificar el idioma de tu página agregando el atributo lang al elemento html.

Añade un atributo lang con el valor en a la etiqueta de apertura del elemento html para especificar que el lenguaje de la página es el inglés.

Paso 41
Todas las páginas deben comenzar con <!DOCTYPE html>. Esta cadena especial se conoce como declaración y garantiza que el navegador intente cumplir con las especificaciones de la industria.

<!DOCTYPE html> le dice a los navegadores que el documento es un documento HTML5 la cual es la última versión de HTML.

Añade esta declaración como la primera línea del código.

Paso 42
Puedes establecer el comportamiento del navegador añadiendo elementos meta en el head. Aquí tienes un ejemplo:

Código de ejemplo
<meta attribute="value">
Dentro del elemento head, anida un elemento meta con un atributo charset establecido al valor UTF-8. Esto indica al navegador cómo codificar los caracteres de la página.

Ten en cuenta que el elemento meta es un elemento vacío.

Con ese último cambio, has completado el taller de la aplicación de fotos de gatos. ¡Felicidades!

