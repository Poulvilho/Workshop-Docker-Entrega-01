FROM node:14

WORKDIR /chatservice

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 7101

CMD [ "node", "server.js" ]