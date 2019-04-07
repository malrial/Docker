# especificar imagen base

FROM node:alpine

WORKDIR /usr/app

# Instalar dependencias

COPY ./package.json ./
RUN npm install
COPY ./ ./

# Comandos por defecto

CMD ["npm","start"]