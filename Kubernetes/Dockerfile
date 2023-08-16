FROM node:19.9.0-alpine

WORKDIR /app

COPY package*.json /app/

RUN npm i

COPY . /app/

ENV NODE_ENV=docker

CMD [ "npm", "start" ]