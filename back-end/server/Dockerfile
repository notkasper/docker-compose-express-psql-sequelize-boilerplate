FROM node:latest
RUN mkdir /app
WORKDIR /app
COPY . /app
RUN npm install
RUN npm i -g nodemon
CMD node ./server.js
EXPOSE 80