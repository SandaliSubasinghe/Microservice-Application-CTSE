FROM node:latest

WORKDIR /app

copy . . 

RUN npm install

EXPOSE 6060

ENTRYPOINT ["node", "index.js"]