FROM node:20

WORKDIR /Productos
COPY src/controllers /Productos/src/controllers
COPY src/models /Productos/src/models
COPY src/index.js /Productos/src

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

EXPOSE 3002

CMD node src/index.js
