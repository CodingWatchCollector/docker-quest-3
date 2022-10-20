FROM node:lts-alpine

RUN mkdir /app
COPY package*.json ./
RUN npm i
COPY src src
COPY public public

CMD npm start