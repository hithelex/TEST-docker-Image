# My Docker Images

Este repositorio contiene varias imágenes Docker para diferentes aplicaciones.

## Node.js App

Para construir y ejecutar la imagen de la aplicación Node.js:

```bash
cd node-app
docker build -t node-app .
docker run -p 3000:3000 node-app

