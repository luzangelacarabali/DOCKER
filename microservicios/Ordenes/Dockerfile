FROM node:20

WORKDIR /ordenes
COPY package.json .
COPY  package-lock.json .
RUN npm install

EXPOSE 3003

COPY . .
CMD npm start
