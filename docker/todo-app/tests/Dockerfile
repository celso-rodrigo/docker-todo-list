FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests/

ENTRYPOINT [ "npm", "test" ]

ADD node_modules.tar.gz .

COPY . .
