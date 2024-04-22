FROM node:latest

EXPOSE 3003

WORKDIR /Ordenes

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

COPY src/controllers /Ordenes/src/controllers
COPY src/models /Ordenes/src/models
COPY src/index.js /Ordenes/src

CMD node index.js
