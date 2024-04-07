#specify base omage
FROM node:18-alpine

#work directory
WORKDIR /usr/app

COPY package.json ./

RUN npm install

COPY ./ ./


CMD ["npm","start"]


