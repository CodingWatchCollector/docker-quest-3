FROM node:lts-alpine

RUN mkdir /app
COPY package*.json ./
RUN npm i
COPY src src

CMD npm start