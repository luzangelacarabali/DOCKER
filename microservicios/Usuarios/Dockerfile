FROM node:latest

EXPOSE 3001

WORKDIR /Usuarios

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

COPY src/controllers /Usuarios/src/controllers
COPY src/models /Usuarios/src/models
COPY src/index.js /Usuarios/src

CMD node index.js
