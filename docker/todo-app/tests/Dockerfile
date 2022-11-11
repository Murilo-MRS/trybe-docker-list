FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm", "test" ]