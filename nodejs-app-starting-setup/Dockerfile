FROM node:14

WORKDIR /app

COPY package.json /app

COPY . /app

RUN npm install

COPY . /app

EXPOSE 80

CMD [ "node", "server.js" ]

