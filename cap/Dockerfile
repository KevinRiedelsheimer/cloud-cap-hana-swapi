FROM node:16.15.1
ENV VERSION 1.0
WORKDIR /app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
CMD [ "node", "server.js" ]