FROM node:lts-alpine3.14

WORKDIR /usr/src/app

COPY ./src/package.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]




