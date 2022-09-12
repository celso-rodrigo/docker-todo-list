FROM node:14-alpine3.15

WORKDIR /front-end/

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]

ADD ./node_modules.tar.gz .

COPY . .
