# 00054621_practica1_secci-n1
Laboratorio no.1 Programación Web

Preguntas Laboratorio:

1. ¿Hay cambios en la visualización del sitio web? Si la
respuesta es negativa, piense un momento ¿Para qué sirven las etiquetas meta? Busque esa respuesta en la
introducción teórica de la guía o consulte con una búsqueda de su duda en google.

R// No. No hay cambios en la visualización porque las etiquetas <meta> no renderizan nada; aportan metadatos dentro de <head>. Sirven para describir la página (description, keywords, author), definir la codificación (charset), configurar el viewport en móviles y dar directrices a buscadores/robots y redes sociales. Por eso no alteran la apariencia del sitio.

2. ¿Qué pasaría si la imagen esta guardada en la misma carpeta de la página web? ¿Y si está en una carpeta superior?

R// Si la imagen está en la misma carpeta que la página, usa una ruta relativa simple:
<img src="imagen.jpg" alt="..."> (también válido ./imagen.jpg).
Si está en una carpeta superior, sube un nivel con ..:
<img src="../imagen.jpg" alt="...">.
Si en el nivel superior hay una carpeta (p. ej., imagenes), usa:
<img src="../imagenes/imagen.jpg" alt="...">.
(En la guía, cuando la imagen está en una subcarpeta del proyecto, se usa src="imagenes/imagen.jpg")

3. Pregúntese, ¿Cómo se consigue que el último enlace se abra en una nueva ventana?

R// Añadiendo el atributo target="_blank" al último enlace, por ejemplo:
<a href="http://www.uca.edu.sv" target="_blank">aquí</a> — así se abre en una nueva ventana/pestaña

4. ¿El resultado obtenido es similar al esquema HTML mostrado en la figura de la introducción teórica para elementos semánticos? ¿Por qué? Razónelo y/o consulte con su instructor.

R//Sí, es similar en estructura semántica (aunque no idéntico en apariencia). El archivo usa las etiquetas de HTML5 que el esquema resalta: <header> para el encabezado con el título, <nav> para el menú, <section> como contenedor del contenido principal, múltiples <article> (uno por país), <aside> para contenido complementario, y <footer> para el pie de página.