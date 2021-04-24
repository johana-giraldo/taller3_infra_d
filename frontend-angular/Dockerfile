#base imagen
FROM node:12.2.0
# crear carpeta donde se copiara el codigo de la aplicacion
WORKDIR /app

#copiando el codigo de la aplicacion
COPY . /app

#instalando dependencias
RUN npm install
RUN npm install -g @angular/cli@7.3.9

# iniciando la aplicacion 
CMD ng serve --host 0.0.0.0 --disable-host-check --port=3000
