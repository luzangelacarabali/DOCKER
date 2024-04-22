FROM node:latest

EXPOSE 3002

WORKDIR /Productos

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

COPY src/controllers /Productos/src/controllers
COPY src/models /Productos/src/models
COPY src/index.js /Productos/src

CMD node index.js
