FROM node:14.15-alpine

WORKDIR /auth-service

COPY ./package.json ./package-lock.json ./
RUN npm install

RUN mkdir ./src
COPY ./src ./src

CMD ["node", "./src/server.js"]
