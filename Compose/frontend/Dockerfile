FROM node:14-alpine3.14

WORKDIR /usr/src/app 

COPY package*.json .

RUN npm install

COPY . .

RUN npm run build 

RUN npm install -g serve