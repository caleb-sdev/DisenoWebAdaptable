¿Qué papel desempeña el HTML en la red?
¿Qué es HTML?
HTML, que significa HyperText Markup Language, es un lenguaje de marcado para crear páginas web. Cuando visitas un sitio web y ves contenido como párrafos, títulos, enlaces, imágenes y videos, eso es HTML.

Aquí tienes un pequeño ejemplo usando elementos HTML. Prueba a editar parte del texto en el editor y verás los cambios actualizarse en la ventana de vista previa.

<h1>Main heading element</h1>

<p>I am a paragraph element.</p>
HTML representa el contenido y la estructura de una página web mediante el uso de elementos. La mayoría de los elementos tendrán una etiqueta de apertura y una de cierre. A veces, esas etiquetas se denominan etiquetas de inicio y de fin. Entre esas dos etiquetas, tendrás el contenido. Este contenido puede ser texto o otros elementos HTML.

Aquí tienes otro ejemplo de un elemento de párrafo. Cambia el texto en el editor para que diga I love coding! y observa los resultados en la ventana de vista previa.

<p>I am a paragraph element.</p>
Etiquetas de apertura y cierre
Tanto las etiquetas de apertura como las de cierre comienzan con un corchete angular izquierdo (<) y terminan con un corchete angular derecho (>), con el nombre de la etiqueta colocado entre estos corchetes angulares. Aunque los nombres de las etiquetas HTML no distinguen entre mayúsculas y minúsculas, es una convención ampliamente aceptada y una buena práctica escribirlas en minúsculas.

Aquí hay un vistazo más de cerca solo a las etiquetas de apertura y cierre del párrafo:

<p>
</p>
Lo que distingue una etiqueta de apertura de una de cierre es la barra diagonal (/) colocada inmediatamente después del corchete angular izquierdo en una etiqueta de cierre. Algunos elementos HTML no tienen etiqueta de cierre. Estos se conocen como elementos vacíos.

Elementos vacíos
Aquí hay un ejemplo de un elemento de imagen que es un elemento vacío:

<img>
Observa que este elemento de imagen no tiene etiqueta de cierre y no tiene contenido. Los elementos vacíos no pueden tener contenido y solo tienen una etiqueta de inicio.

A veces verás elementos void que usan un / antes del > así:

<img />
Aunque muchos formateadores de código como Prettier eligen incluir el / en elementos void, la especificación de HTML indica que la presencia del / "no marca la etiqueta de inicio como autocerrada sino que es innecesaria y no tiene ningún efecto".

En el desarrollo real, verás ambas formas, por lo que es importante estar familiarizado con las dos.

Atributos de HTML
Si quieres mostrar una imagen, necesitarás incluir un par de atributos dentro de tu elemento de imagen. Un atributo es un valor especial que se usa para ajustar el comportamiento de un elemento HTML.

Aquí tienes un ejemplo de un elemento de imagen con un atributo src. Actualiza el valor del atributo src a "https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" y verás que la imagen cambia a dos gatos durmiendo pacíficamente.

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg" />
El atributo src se utiliza para especificar la ubicación de esa imagen. Para los elementos de imagen, es una buena práctica incluir otro atributo llamado el atributo alt. El atributo alt se utiliza para proporcionar un texto descriptivo breve para las imágenes.

Aquí tienes un ejemplo de un elemento de imagen con los atributos src y alt. Intenta romper la imagen actualizando el valor de src a "https://.freecodecamp.org/curriculum/cat-photo-app/cats.jpg". Verás que la imagen desaparece y solo se muestra el texto de alt.

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch." />
El rol de HTML junto con CSS y JavaScript
Entonces, te podrías preguntar si HTML por sí solo es suficiente para construir un sitio web. Bueno, la respuesta es: depende. Si estás construyendo un pequeño proyecto de práctica que solo muestra texto e imágenes, HTML por sí solo podría ser suficiente. Sin embargo, si estás creando un sitio web profesional moderno, necesitarás tener HTML, CSS y JavaScript.

HTML es para el contenido y la estructura. CSS es para el estilo. JavaScript es para agregar interactividad a tus páginas web. Una buena analogía para esto es comparar HTML, CSS y JavaScript con un edificio completo.

HTML representa los bloques, el concreto y el hierro que forman las paredes. Es la base que hace que el edificio sea fuerte. CSS representa el diseño interior y exterior que hace que el edificio se vea hermoso. JavaScript representa el sistema eléctrico y de agua que asegura el acceso ininterrumpido a agua y electricidad.


¿Qué son los atributos y cómo funcionan?
¿Qué es un atributo?
Un atributo es un valor colocado dentro de la etiqueta de apertura de un elemento HTML. Los atributos proporcionan información adicional sobre el elemento o especifican cómo debe comportarse el elemento. Aquí está la sintaxis básica de un atributo:

<element attribute="value"></element>
El nombre del atributo es seguido por un signo igual (=) y un valor entre comillas. El valor puede ser una cadena o un número, dependiendo del atributo.

Los atributos href y target
Este primer ejemplo usa los atributos href y target. El atributo href especifica la URL de un enlace y el atributo target especifica dónde abrir el enlace.

Nota: El elemento a, también conocido como elemento ancla, se usa para crear hipervínculos. El texto entre las etiquetas a de apertura y cierre es la parte clickeable que los usuarios seleccionan para navegar.

Activa el editor interactivo y cambia el href="https://www.freecodecamp.org/news/" a href="https://www.freecodecamp.org". Ahora, cuando hagas clic en el enlace del editor interactivo, verás la página principal de freeCodeCamp en una nueva pestaña del navegador.

<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>
Sin el atributo href, el enlace no funcionaría porque no habría una URL de destino. Por eso debes incluir este atributo href para que el enlace sea funcional. El target="_blank" permite que el enlace se abra en una nueva pestaña del navegador. Aprenderás más sobre el atributo target en lecciones futuras.

Los atributos src y alt
Otros atributos comunes son los atributos src y alt, o alternativos, que se usan para especificar la fuente de una imagen y proporcionar un texto descriptivo alternativo para la imagen, respectivamente.

Activa el editor interactivo y cambia el src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" a src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg". Luego cambia el alt="Two tabby kittens sleeping together on a couch." a alt="Two cats running in the dirt.".

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch." />
Al igual que el atributo href, el atributo src es obligatorio porque especifica el archivo de imagen que se mostrará. El atributo alt no es obligatorio, pero se recomienda por motivos de accesibilidad. La accesibilidad significa asegurarse de que todos, incluidas las personas con discapacidades, puedan usar y entender cosas como sitios web, apps y espacios físicos. Aprenderás más sobre accesibilidad en las próximas lecciones.

El atributo checked
Algunos atributos son un poco únicos con su sintaxis, como el atributo checked.

Activa el editor interactivo y prueba hacer clic en la casilla de verificación en la ventana de vista previa para ver cómo alterna entre un estado marcado y desmarcado.

<input type="checkbox" checked />
En el siguiente ejemplo, tenemos un elemento input con el atributo type establecido en checkbox. Los inputs se usan para recopilar datos de los usuarios, y el atributo type especifica el tipo de entrada. En este caso, esta entrada es una casilla de verificación. Aprenderás más sobre cómo funcionan los inputs en las próximas lecciones.

El atributo checked se utiliza para especificar que la casilla de verificación debe estar marcada por defecto. El atributo checked no requiere un valor. Si está presente, la casilla estará marcada por defecto. Si el atributo no está presente, la casilla de verificación estará desmarcada. Esto se conoce como un atributo booleano. Aprenderás más sobre los booleanos en general cuando llegues a la sección de JavaScript.

Activa el editor interactivo e intenta eliminar el atributo checked del input. Verás que la casilla ya no está marcada por defecto.

<input type="checkbox" checked />
Otros atributos booleanos
Hay varios atributos booleanos comunes que encontrarás en HTML, como disabled, readonly, y required. Estos atributos se utilizan para especificar el estado de un elemento, como si está deshabilitado, es de solo lectura, o es requerido.

Aquí tienes un ejemplo de un elemento de texto input que está deshabilitado por defecto. Activa el editor interactivo y prueba hacer clic en el elemento input en la ventana de vista previa. Ahora elimina el atributo disabled del elemento input y verás que el input ya no está deshabilitado por defecto. Ahora deberías poder hacer clic en él y escribir dentro del campo.

<input type="text" disabled>
HTML tiene muchos atributos que se pueden usar para personalizar el comportamiento y la apariencia de los elementos en una página web. Entender cómo usar los atributos es esencial para crear contenido web interactivo y accesible. En las próximas lecciones, aprenderás sobre más atributos de HTML y cómo usarlos eficazmente en tus proyectos de desarrollo web.
