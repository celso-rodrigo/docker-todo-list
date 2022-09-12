FROM node:14-alpine3.15

WORKDIR /usr/src/app

EXPOSE 3001

COPY package*.json ./

ADD ./node_modules.tar.gz .

COPY . .

RUN npm install

CMD [ "npm", "start" ]
