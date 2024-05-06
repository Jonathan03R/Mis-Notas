# Creación de Backend con Node.js

Este proyecto muestra cómo crear un backend básico utilizando Node.js. Sigue los pasos a continuación para configurar tu propio backend:

## Pasos para Crear el Backend

1. **Instalación de Node.js:** Si no tienes Node.js instalado en tu sistema, descárgalo e instálalo desde [Node.js website](https://nodejs.org/).

2. **Inicialización del Proyecto:** Crea un nuevo directorio para tu proyecto y abre una terminal en ese directorio. Luego, inicializa un nuevo proyecto Node.js ejecutando el siguiente comando:

        $ npm init 
3. **Instalación de Dependencias:** Instala las dependencias necesarias para tu backend. Ejecuta el siguiente comando en tu terminal para instalar las dependencias `express`, `mysql`, `dotenv` y `cors`:

       npm install --save express mysql dotenv cors
- `express`: Un framework web para Node.js que facilita la creación de aplicaciones web y APIs.
- `mysql`: Un paquete de Node.js para interactuar con bases de datos MySQL.
- `dotenv`: Un módulo para cargar variables de entorno desde un archivo `.env` en tu aplicación.
- `cors`: Un paquete de Node.js para habilitar el intercambio de recursos de origen cruzado (CORS) en tu servidor Express.

4. **Creación de Archivos:** Crea los archivos necesarios para tu backend, como `app.js` para el punto de entrada de la aplicación y otros archivos para definir las rutas, modelos de datos, etc. Además, instala `nodemon` como una dependencia de desarrollo para facilitar el desarrollo:

       npm install --save-dev nodemon

- `nodemon`: Una herramienta que ayuda a desarrollar aplicaciones Node.js reiniciando automáticamente la aplicación cuando se detectan cambios en el código fuente. Es especialmente útil durante el desarrollo para evitar tener que reiniciar manualmente el servidor después de cada cambio.


## Estructura del Proyecto

El proyecto puede seguir una estructura de carpetas comúnmente utilizada para aplicaciones Node.js. Aquí hay una posible estructura de archivos y carpetas para tu backend:

- `app.js`: El punto de entrada de la aplicación donde se configura y se inicia el servidor Express.
- `routes/`: Carpeta que contiene archivos para definir las rutas de la aplicación.
- `models/`: Carpeta que contiene archivos para definir los modelos de datos y la interacción con la base de datos.
- `config/`: Carpeta opcional para almacenar archivos de configuración, como variables de entorno.
- `public/`: Carpeta opcional para archivos estáticos, como archivos HTML, CSS y JavaScript para servir en la aplicación.

## Instrucciones de Uso

1. **Instalación de Dependencias:** Antes de comenzar a ejecutar tu proyecto, asegúrate de instalar todas las dependencias necesarias ejecutando el siguiente comando en la terminal:

   ```bash
   npm install
2. **Iniciar el Servidor:** Para hacer correr el servidor en un puerto local que hayas especificado en tu archivo .env, ejecuta el siguiente comando en tu terminal:

   ```bash
   npm start
