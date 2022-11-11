FROM node:14-alpine

WORKDIR /todoapp/front-end

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm", "start" ]