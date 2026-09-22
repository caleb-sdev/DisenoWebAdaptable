¿Cuál es el papel del elemento de enlace en HTML y cómo se puede usar para enlazar a hojas de estilo externas?
Aprendamos sobre el elemento link y cómo usarlo para enlazar a hojas de estilo externas.

El elemento link se usa para enlazar a recursos externos como hojas de estilo e íconos del sitio. Aquí está la sintaxis básica para usar el elemento link para un archivo CSS externo:

<link rel="stylesheet" href="./styles.css" />
El atributo rel se usa para especificar la relación entre el recurso enlazado y el documento HTML. En esta situación, necesitamos especificar que este recurso enlazado es una stylesheet.

Se considera una buena práctica separar el HTML y CSS en diferentes archivos. Los desarrolladores usarán el elemento link para sus archivos CSS externos en lugar de escribir todo en el documento HTML.

El atributo href se usa para especificar la ubicación del URL para el recurso externo.

El . seguido de una barra diagonal en el ejemplo indica a la computadora que busque en la carpeta o directorio actual el archivo styles.css.

El elemento link debe colocarse dentro del elemento head como se ve en el siguiente ejemplo:

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Examples of the link element</title>
  <link rel="stylesheet" href="./styles.css" />
</head>
A menudo verás múltiples elementos link dentro de un código profesional que enlazan a diferentes hojas de estilo, fuentes e íconos. Aquí tienes un ejemplo de cómo usar el elemento link para enlazar a una fuente externa de Google llamada Playwrite Cuba:

<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap"
  rel="stylesheet"
/>
Google Fonts son un conjunto de fuentes personalizables gratuitas y de código abierto que puedes usar dentro de cualquier proyecto. Puedes elegir qué fuentes te gustaría usar y Google te proporcionará el código HTML y CSS necesario. En este ejemplo, el valor preconnect para el atributo rel le dice al navegador que cree una conexión anticipada con el valor especificado en el atributo href. Esto se hace para acelerar los tiempos de carga de estos recursos externos.

Otro caso de uso común para el elemento link es enlazar a íconos. Aquí hay un ejemplo de enlace a un favicon:

<link rel="icon" href="favicon.ico" />
Un favicon, que es la abreviatura de favorite icon, es un ícono pequeño que normalmente se muestra en la pestaña del navegador junto al título del sitio. Muchos sitios web usan un favicon para mostrar el ícono de su marca.

¿Qué es un boilerplate HTML y por qué es importante?
Aprendamos sobre el boilerplate HTML.

¿Qué es el código repetitivo de HTML, preguntas? Es como una plantilla lista para tus páginas web. Piénsalo como los cimientos de una casa. Un código repetitivo incluye la estructura básica y los elementos esenciales que todo documento HTML necesita. Te ahorra tiempo y ayuda a que tus páginas estén configuradas correctamente. Aquí tienes un ejemplo:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>freeCodeCamp</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
  </body>
</html>
Analicemos las partes clave de este boilerplate. Primero, está la declaración DOCTYPE:

<!DOCTYPE html>
Le dice a los navegadores qué versión de HTML estás utilizando. A continuación, viene la etiqueta html:

<!DOCTYPE html>
<html lang="en">
  <!--All other elements go inside here-->
</html>
Esto envuelve todo tu contenido y puede especificar el idioma de tu página. Dentro de la etiqueta html, encontrarás dos secciones principales, un head y un body:

<!DOCTYPE html>
<html lang="en">
  <head>
    <!--Important metadata goes here-->
  </head>
  <body>
    <!--Headings, paragraphs, images, etc. go inside here-->
  </body>
</html>
La sección head contiene información importante tras bambalinas:

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document Title Goes Here</title>
  <link rel="stylesheet" href="./styles.css" />
</head>
Los metadatos de tu sitio, contenidos en elementos meta, tienen detalles sobre cosas como la codificación de caracteres y cómo sitios como Twitter deberían mostrar la vista previa del enlace de tu página. El título de tu sitio, encontrado en el elemento title, determina el texto que aparece en la pestaña o ventana del navegador. Finalmente, generalmente se vinculan las hojas de estilo externas de tu página en la sección head usando elementos link.

La sección body es donde va todo tu contenido:

<body>
  <h1>I am a main title</h1>
  <p>Example paragraph text</p>
</body>
Ahora, ¿por qué es importante un boilerplate? Asegura que tus páginas estén estructuradas correctamente y funcionen bien en diferentes navegadores. Usar un boilerplate te ayuda a evitar errores comunes y seguir las mejores prácticas. Es un gran punto de partida para cualquier proyecto web. Recuerda, puedes personalizar tu propio boilerplate para adecuarse a tus necesidades. A medida que ganes experiencia, podrías añadir tus propios elementos preferidos o etiquetas meta. Al continuar mejorando tu boilerplate personal, descubrirás que te ahorra tiempo al comenzar nuevos proyectos.

La próxima vez que inicies un nuevo archivo HTML, considera usar un boilerplate. Definitivamente te dará una base sólida sobre la cual construir.

¿Qué es la codificación de caracteres UTF-8, y por qué es necesaria?
UTF-8, o UCS Transformation Format 8, es una codificación de caracteres estandarizada ampliamente usada en la web. La codificación de caracteres es el método que usan las computadoras para almacenar caracteres como datos. Esencialmente, todo el texto en una página web es una secuencia de caracteres almacenados como uno o más bytes. En informática, un byte es una unidad de datos que consiste en 8 bits, o dígitos binarios. UTF-8 soporta todos los caracteres del conjunto de caracteres Unicode, e incluye caracteres y símbolos de todos los sistemas de escritura, idiomas y símbolos técnicos. Aquí tienes un ejemplo de cómo usar el elemento meta con el atributo charset para establecer la codificación de caracteres a UTF-8:

<meta charset="UTF-8" />
Al establecer la codificación de caracteres en UTF-8, se asegurará de que el carácter acentuado "e" (é) se muestre correctamente en la página. Aquí hay un ejemplo de código extendido utilizando la codificación de caracteres UTF-8:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Examples of the UTF-8 encoding</title>
  </head>
  <body>
    <p>Café</p>
  </body>
</html>
Para cada nuevo proyecto que crees, debes incluir este elemento meta con el atributo charset configurado en UTF-8.