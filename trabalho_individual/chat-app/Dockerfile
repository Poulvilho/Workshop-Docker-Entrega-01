FROM node:latest

WORKDIR /chatapp

ENV PATH /chatapp/node_modules/.bin:$PATH

COPY package.json /chatapp/package.json
RUN npm install
RUN npm install react-scripts@3.3.1 -g

EXPOSE 7001

CMD ["npm", "start"]