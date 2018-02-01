FROM node:carbon

WORKDIR /usr/src/app

# copiamos los arhivos necesarios
COPY package.json ./
COPY package-lock.json ./

# este es el servicio
COPY api.js ./

RUN npm install

EXPOSE 8080

CMD ["npm", "start" ]

