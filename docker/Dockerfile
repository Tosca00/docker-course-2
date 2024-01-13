FROM node:19-alpine

WORKDIR /app

COPY /app/package.json ./
COPY /app/server.js ./

RUN npm install

EXPOSE 3001

CMD [ "node", "server.js" ]
