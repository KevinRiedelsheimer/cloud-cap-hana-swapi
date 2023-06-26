FROM node:16.15.1
ENV VERSION 1.0
WORKDIR /cap/app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
CMD [ "node", "server.js" ]