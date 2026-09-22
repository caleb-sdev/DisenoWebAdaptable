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

