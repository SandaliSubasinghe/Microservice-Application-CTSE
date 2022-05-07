FROM node:latest
WORKDIR /ecommerce-microservice-master/product-service
COPY . .
RUN npm install
EXPOSE 8080
ENTRYPOINT ["node", "index.js"]
