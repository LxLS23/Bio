#Crear la imagen desde un mginx de alpine
FROM nginx:alpine

#Elimina todos los archivos por defecto que trae el nginx
RUN rm -rf /usr/share/nginx/html/*

#Copia todo el proyecto a la carpeta de nginx
COPY . /usr/share/nginx/html

#Expón el puerto donde correra la app
EXPOSE 80