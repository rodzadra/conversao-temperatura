FROM node:14.7-alpine3.12

WORKDIR /home/app
COPY package*.json .
RUN npm install
COPY . .
CMD ["node","server.js"]