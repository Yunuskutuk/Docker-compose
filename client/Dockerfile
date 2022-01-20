FROM node:lts-alpine

WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src src
COPY public public
EXPOSE 3000
CMD npm start