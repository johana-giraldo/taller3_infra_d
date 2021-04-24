#base image
FROM node:14-stretch

# Crear carpeta donde se copiara el código de la aplicacion
WORKDIR /code

# Copiando el código de la aplicación
COPY . /code

# Instalando dependencias
RUN npm i

#Iniciando aplicación
CMD node app.js
