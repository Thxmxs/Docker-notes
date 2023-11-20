#Para montar imagen de nuestra app de node
FROM node:19.2-alpine3.16

# cd app dentro del container
WORKDIR /app

# copia app.js y package.json en /app/
COPY app.js package.json ./

#instalar las dependencias
RUN npm install

#iniciamos backend
CMD [ "node", "app.js" ]

# ahora vamos a la termina y ejecutamos docker build --tag cron-ticker .
# Corremos la imagen docker container run cron-ticker+

