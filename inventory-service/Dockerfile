FROM node:latest
WORKDIR /inventory-service
ENV PORT 6000
COPY package.json /inventory-service/package.json
RUN npm install
COPY . /inventory-service
CMD npm start