FROM node:14.15-alpine

WORKDIR /api-solution

COPY ./package.json ./package-lock.json ./
RUN npm install

COPY ./src ./src

CMD ["node", "./src/index.js"]