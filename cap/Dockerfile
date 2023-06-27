FROM node:16.15.1

ENV VERSION 1.0

# Create app directory
WORKDIR /usr/src/app

COPY /package*.json ./

RUN npm install

COPY /. .

CMD [ "cds", "run" ]