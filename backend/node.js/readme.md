# Creación de Backend con Node.js

Este proyecto muestra cómo crear un backend básico utilizando Node.js. Sigue los pasos a continuación para configurar tu propio backend:

## Pasos para Crear el Backend

1. **Instalación de Node.js:** Si no tienes Node.js instalado en tu sistema, descárgalo e instálalo desde [Node.js website](https://nodejs.org/).

2. **Inicialización del Proyecto:** Crea un nuevo directorio para tu proyecto y abre una terminal en ese directorio. Luego, inicializa un nuevo proyecto Node.js ejecutando el siguiente comando:

`$ npm init `
3. **Instalación de Dependencias:** Instala las dependencias necesarias para tu backend. Ejecuta el siguiente comando en tu terminal para instalar las dependencias `express`, `mysql`, `dotenv` y `cors`:
`npm install --save express mysql dotenv cors`
- `express`: Un framework web para Node.js que facilita la creación de aplicaciones web y APIs.
- `mysql`: Un paquete de Node.js para interactuar con bases de datos MySQL.
- `dotenv`: Un módulo para cargar variables de entorno desde un archivo `.env` en tu aplicación.
- `cors`: Un paquete de Node.js para habilitar el intercambio de recursos de origen cruzado (CORS) en tu servidor Express.

4. **Creación de Archivos:** Crea los archivos necesarios para tu backend, como `app.js` para el punto de entrada de la aplicación y otros archivos para definir las rutas, modelos de datos, etc. Además, instala `nodemon` como una dependencia de desarrollo para facilitar el desarrollo: `npm install --save-dev nodemon`

- `nodemon`: Una herramienta que ayuda a desarrollar aplicaciones Node.js reiniciando automáticamente la aplicación cuando se detectan cambios en el código fuente. Es especialmente útil durante el desarrollo para evitar tener que reiniciar manualmente el servidor después de cada cambio.

