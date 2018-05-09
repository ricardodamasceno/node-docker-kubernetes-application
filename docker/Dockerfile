FROM node:latest

MAINTAINER Ricardo Damasceno

COPY ./ /ricardo/docker-images
WORKDIR /ricardo/docker-images

RUN npm install

ENTRYPOINT node index.js

EXPOSE 3000
