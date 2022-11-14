FROM node:14-alpine

WORKDIR /app

EXPOSE 3001

COPY package.json .

COPY package-lock.json .

RUN npm install

COPY . .

ADD node_modules.tar.gz .

CMD [ "npm", "start" ]