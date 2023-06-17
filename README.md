<h1>Calculadora de propinas 🍖🧮</h1>

## Descripción 

Este proyecto es una aplicación que combina diferentes funcionalidades para mejorar la experiencia en un restaurante. La aplicación incluye una calculadora de propinas que permite a los usuarios calcular la propina adecuada según el monto total de su cuenta. Además, ofrece la opción de reservar una mesa, permitiendo a los usuarios seleccionar una fecha y hora para su visita.

Una de las características destacadas de esta aplicación es la integración de un menú de platillos. La aplicación utiliza json-server para crear una API que proporciona los datos de los platillos disponibles en el restaurante. Los usuarios pueden ver el menú completo, incluyendo los nombres de los platillos, precios y cualquier otra información relevante. Esta información se obtiene a través de consultas asincrónicas a la API, lo que permite una carga rápida y eficiente de los datos.

En resumen, este proyecto combina el uso de funciones asincrónicas, consultas a una API creada con json-server y diversas funcionalidades relacionadas con la experiencia en un restaurante. Proporciona una solución práctica y completa para aquellos que desean calcular propinas, reservar mesas y explorar el menú de platillos, todo dentro de una sola aplicación fácil de usar.

## Requisitos

 - Node.js: Asegúrate de tener Node.js instalado en tu máquina. Puedes descargarlo desde [NodeJS](https://nodejs.org)
 - Con eso se deberia instalar npm igualmente
 - Para verifivar la instalación de [Node](https://nodejs.org), ejecuta  <code>node -v </code>
 - Igualmente con npm  <code> npm -v </code>

## Instalación

 1. Clona o descarga el repositorio en tu máquina
 2. Navega hasta la carpeta del proyecto
 3. Instala json-server globalmente usando el siguiente comando  <code>npm install -g json-server</code>
 4. Verificar la instalación con  <code>json-server -v </code> . Luego impletar la base de datos del archivo db.json
    - En la carpeta del proyecto ejecuta  <code>json-server --watch db.json --port 4000 </code>
    - Tiene que ser en el puerto 4000 ya que asi esta implementado en el codigo.
    - Para cerrar con CTRL + C, en la terminal
    
## Autor ✒️

**Yechua Silva**

* [LinkedIn](https://www.linkedin.com/in/yechua-silva/)

