Paso 1
En este taller, construirás una página de librería creando tarjetas de libros que muestran información sobre diferentes libros. Practicarás organizar contenido usando elementos div, clases e IDs.

Comienza tu página de librería creando la estructura básica de HTML.

Agrega la declaración <!DOCTYPE html> y los elementos html y head.

Agrega un atributo lang al elemento html y configúralo en "en".

Paso 2
Agrega el elemento title dentro del elemento head.

Establece el título de la página en XYZ Bookstore Page.


Paso 3
Ahora, mejora la estructura de tu documento HTML para asegurar que tu página esté codificada correctamente.

Dentro del elemento head, agrega el elemento <meta charset="UTF-8">.

Por último, agrega un elemento body debajo de la sección head. Aquí es donde irá todo el contenido visible de tu página.

Paso 4
En este paso, agrega un elemento h1 con el texto XYZ Bookstore.

Paso 5
Debajo del elemento h1, agrega un elemento p con este texto: Browse our collection of amazing books!.

Paso 6
El elemento div se usa como contenedor para agrupar otros elementos HTML. Principalmente usarás el elemento div cuando quieras agrupar elementos HTML que compartirán un conjunto de estilos CSS.

Debajo del elemento p, agrega un elemento div. Este div será un contenedor para tus tarjetas de libros.

Nota: Este taller no aplica CSS. Las clases y los elementos agrupados son útiles para el estilo CSS, pero en este taller se usan solo para estructurar y agrupar contenido. Aprenderás cómo funciona el estilo en un módulo posterior.

Paso 7
El atributo class se usa para identificar uno o más elementos para el estilo. A diferencia del atributo id, los nombres de clase no necesitan ser únicos: varios elementos pueden compartir la misma clase.

Aquí hay un ejemplo:

Código de ejemplo
<p class="example">example paragraph</p>
Agrega un atributo class a tu elemento div y establece su valor en card-container.

Paso 8
Puedes agregar múltiples elementos dentro de un elemento div para agrupar contenido relacionado. Dentro del elemento que tiene una class de card-container, crea otro elemento div. Este div representará la primera tarjeta de libro.

Agrega un atributo class a este nuevo elemento div y establece el valor del atributo class en card.

Paso 9
El atributo id añade un identificador único a un elemento HTML. Cada id debe ser único dentro de una página y solo debe usarse una vez.

Los valores de id no pueden contener espacios y solo deben contener letras, dígitos, guiones bajos y guiones.

Aquí hay un ejemplo:

Código de ejemplo
<p id="para">example paragraph</p>
Agrega un atributo id a tu elemento que tenga una clase card y establece su valor en sally-adventure-book.

Paso 11
Debajo del elemento h2 en el primer elemento que tenga una clase card, agrega un elemento p con el siguiente texto:

Código de ejemplo
This is an epic story of Sally and her dog Rex as they navigate through other worlds.

Paso 12
El elemento button se usa para crear botones clicables en una página web. Los botones son elementos interactivos que los usuarios pueden clicar para realizar acciones.

Agrega un elemento button dentro del elemento que tiene un class de card, dale al botón un atributo class establecido en btn y el texto Buy Now.

Paso 13
Ahora crea una segunda tarjeta de libro. Añade otro elemento div con el atributo class establecido en card. Observa cómo puedes reutilizar el mismo nombre de clase para múltiples elementos y aplicar un estilo consistente.

Paso 15
Dentro del segundo elemento que tiene una clase card, agrega un elemento h2 con el texto Dave's Cooking Adventure.

Paso 16
Debajo del elemento h2 en la segunda tarjeta, agrega un elemento p con este texto:

Código de ejemplo
This is the story of Dave as he learns to cook everything from pancakes to pasta, one recipe at a time.

Paso 17
Dentro de la segunda tarjeta, agrega un elemento button con el atributo class establecido en btn y el texto Buy Now.

Ambos elementos button ahora comparten la misma class, lo que significa que pueden ser estilizados de manera consistente juntos.

Paso 18
Recuerda, un elemento HTML se ve así:

Código de ejemplo
<element attribute="value">
    inner text
</element>
Debajo del elemento con la clase card-container, agrega un nuevo elemento p con este texto:

Código de ejemplo
Review your selections and continue to checkout.
Debajo del elemento p, crea un elemento div con el atributo class establecido en btn-container. Este contenedor agrupará tus elementos de botón de navegación.

Paso 19
Dentro del elemento con una clase btn-container, agrega dos elementos button:

Primer botón:

Id: view-cart-btn
Clase: btn
Texto: View Cart
Segundo botón:

Id: checkout-btn
Clase: btn
Texto: Checkout
¡Felicidades! Has construido con éxito la estructura de una página de librería usando divs, clases e ids para organizar tu contenido.t