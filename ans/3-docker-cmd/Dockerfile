FROM node:10.19.0-alpine

COPY . .

RUN  npm install

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD ["run", "start"]