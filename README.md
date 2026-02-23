# SEAstartup — Documento de Reflexión

**Equipo:** Alexandra · Sebastián · Elkin  
**Asignatura:** Ingeniería Web  
**Entregable:** Actividad práctica — HTML5 semántico


## ¿Qué construimos?

Desarrollamos **SEAstartup**, un sitio web construido únicamente con **HTML5**. Nuestro sitio presenta una plataforma para ayudar a empresas, personas en Colombia y en el mudno entero a crear su presencia digital, algo que sabemos que es vital hoy en dia, incluimos en esta secciones de servicios, información del equipo, contenido educativo sobre ingeniería web y un formulario de contacto.


## Explicación del código

El archivo `index.html` está organizado con etiquetas semánticas de HTML5:

- **`<header>`** — contiene el logo y la barra de navegación con enlaces a cada sección del sitio.
- **`<main>`** — agrupa todo el contenido principal dividido en secciones:
  - `<section id="inicio">` — presenta la propuesta de valor del proyecto.
  - `<section id="quienes">` — muestra la historia del equipo, misión, visión y valores.
  - `<section id="servicios">` — lista los servicios ofrecidos.
  - `<section id="web-moderna">` — contiene el contenido académico requerido por la actividad: un `<article>` que explica la ingeniería web, la arquitectura cliente-servidor y la importancia de la semántica HTML5, junto con un `<aside>` que tiene recursos y enlaces externos recomendados.
  - `<section id="contacto">` — incluye datos de contacto y un formulario.
- **`<footer>`** — muestra los derechos de autor y créditos del equipo.

Y aparte cada bloque del código tiene comentarios que explican su función, lo que facilita entender la estructura sin necesidad de conocimientos previos.



## ¿Qué aprendimos?

Junto con mis compañeros este proyecto nos enseñó que HTML no es solo escribir etiquetas para que algo aparezca en pantalla. Aprendimos que cada etiqueta tiene un propósito y un significado, y que usarlas correctamente hace que el sitio sea más accesible y más fácil de entender tanto para otros desarrolladores como para los navegadores.

También entendimos en la práctica qué es la arquitectura cliente-servidor: el navegador es el cliente que solicita el archivo `index.html` y lo muestra al usuario, mientras que el servidor es quien lo entrega. Aunque nuestro proyecto es estático, ese flujo sigue existiendo.


## Dificultades que tuvimos

La principal dificultad fue organizar bien la estructura semántica. Al principio usábamos etiquetas sin pensar mucho en su significado real, y tuvimos que replantear varias partes del código para que tuviera sentido semántico y no solo visual.

También nos encontramos con errores de validación HTML, como atributos mal escritos y etiquetas que no cerraban correctamente, que tuvimos que identificar y corregir uno por uno.


## Conclusiones

Este proyecto nos dejó claro que la semántica en HTML no es un detalle menor, es la base de cualquier sitio bien construido. Un código que se ve bien en pantalla pero está mal estructurado por dentro va a dar problemas con el tiempo.

También aprendimos que trabajar en equipo sobre un mismo archivo requiere coordinación. Dividir bien las tareas desde el principio nos ayudó a avanzar sin pisarnos entre nosotros.

Fue una buena primera experiencia trabajando un proyecto web de forma ordenada y con criterios técnicos reales.


*© 2025 SEAstartup — Alexandra · Sebastián · Elkin — Ingeniería de Software*
