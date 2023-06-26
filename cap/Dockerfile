FROM node:16.15.1
ENV VERSION x.y
WORKDIR /cap/app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
CMD [ "node", "server.js" ]