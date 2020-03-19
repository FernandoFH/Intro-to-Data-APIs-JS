# Trabajar con datos y API en JavaScript

Este es un documento de trabajo que describe una nueva lista de reproducción de Coding Train: "Trabajar con datos y API en JavaScript".

## Descripción

Este curso es para los aspirantes a desarrolladores que desean aprender a trabajar con datos en aplicaciones web. ¿Cómo recuperar, recopilar y almacenar datos? El curso se impartirá a través de una serie de creación de tres proyectos de datos. El primero será solo del lado del cliente y examinará cómo cargar datos con `fetch ()` y presentarlos en una página web. Los espectadores aprenderán sobre el manejo de eventos asíncronos con Promesas y cómo representar datos en el DOM, así como dibujar en el lienzo HTML5 con p5.js. El segundo y tercer proyecto presentarán el desarrollo de "full stack", agregando programación del lado del servidor con node.js para la persistencia de datos y la autenticación API.

## Introducción
1. Trailer del curso (~ 1 minuto resumen)
2. Introducción completa: descripción general de los temas, objetivos del curso
3. ¿Qué necesito saber para ir al tutorial 1?

### Módulo 1: `fetch ()` con imagen, CSV, JSON

#### 1a: buscar ()
1. ¿Qué es `fetch ()`?
   * [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
   * Promesas, asíncronas y aguardan
   * [Cuerpo - API web](https://developer.mozilla.org/en-US/docs/Web/API/Body)
   * `<img>` elemento DOM
    
#### 1b: Datos tabulares
1. Analizando CSV con `split ()`
2. Gráfico de líneas con [chart.js](https://www.chartjs.org/docs/latest/)

#### 1c: Datos JSON de API
1. Cargar datos JSON con `fetch ()` y actualizar el elemento DOM <span>.
2. Agregue el mapa a la página con [Leaflet.js](https://leafletjs.com/) y coloque la ubicación de ISS como marcador.
3. Actualizando la ubicación continuamente con `setInterval ()`.
  
 #### Objetivos
1. Aprenda `fetch ()` para solicitudes GET con Promesas y `async` /` await`
   * Ver datos de carga de imagen local / JSON / CSV
2. Aprenda a "renderizar" datos con manipulación nativa de JS DOM
3. Descubre piezas faltantes: sin persistencia, las claves API no están ocultas

### Módulo 2: La aplicación Data Selfie

[La aplicación Data Selfie](https://github.com/joeyklee/data-selfie-app) es un tutorial de proyecto de [@joeyklee] (https://github.com/joeyklee).

#### Videos
1. ¿Qué es node, npm y express? Configurar un servidor para alojar páginas estáticas.
2. Accediendo a GeoLocation con `navigator.geolocation`.
3. ¿Qué es un POST? Envío de datos al servidor.
4. ¿Qué es una base de datos? Guardar datos en NeDB.
4. Recuperando datos de NeDB con una ruta "RESTian".
6. Agregar captura e imágenes con p5.
7. Próximos pasos / ejercicio?

#### Objetivos
1. Aprenda los conceptos básicos de la programación del lado del servidor con Node (y express?)
2. Aprenda a guardar datos en una base de datos con [NedB](https://github.com/louischatriot/nedb).
    * muestra solo matriz simple
    * mostrar archivo plano
    * Introducir idea de base de datos
3. Aprenda a usar `fetch ()` para enviar datos al servidor.

### Módulo 3: El clima aquí

[The Weather Here](https://github.com/joeyklee/the-weather-here) es un tutorial del proyecto de [@joeyklee](https://github.com/joeyklee).

#### Objetivos
1. Aprenda a usar `fetch ()` para obtener datos de las API en node.js.
2. Aprenda a almacenar claves API privadas utilizando variables de entorno.
3. Aprenda a implementar su proyecto utilizando servicios como [Glitch](http://glitch.com) y más.

---
#### Lista: [Aqui](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YxDKpFzf_2D84p0cyk4T7X)
