FROM node:lts-alpine

WORKDIR /app

COPY package*.json ./
COPY src src

RUN npm i

CMD npm start