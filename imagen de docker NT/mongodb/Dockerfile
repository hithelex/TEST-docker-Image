# Usa una imagen base de MongoDB
FROM mongo:latest

# Copia el script de inicialización
COPY init-mongo.js /docker-entrypoint-initdb.d/

# Exponer el puerto
EXPOSE 27017

