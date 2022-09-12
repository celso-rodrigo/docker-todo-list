FROM node:14-alpine3.15

WORKDIR /back-end/

EXPOSE 3001

ENTRYPOINT [ "npm", "start" ]

ADD ./node_modules.tar.gz .

COPY . .
