FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

COPY package.json .

COPY package-lock.json .

RUN npm install

COPY . .

ADD node_modules.tar.gz .

CMD [ "npm", "test" ]