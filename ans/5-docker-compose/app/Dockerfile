FROM node:10.19.0-alpine

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . ./

EXPOSE 3000

CMD npm run start
