FROM node:20

WORKDIR /Ordenes
COPY src/controllers /Ordenes/src/controllers
COPY src/models /Ordenes/src/models
COPY src/index.js /Ordenes/src

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

EXPOSE 3003

CMD node src/index.js
