FROM node:20

WORKDIR /Usuarios

COPY src/controllers /Usuarios/src/controllers
COPY src/models /Usuarios/src/models
COPY src/index.js /Usuarios/src

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

EXPOSE 3001

CMD node src/index.js
