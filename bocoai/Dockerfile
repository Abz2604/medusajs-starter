# bocoai/Dockerfile
FROM node:18

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8888

CMD [ "npx", "@medusajs/medusa-cli", "develop" ]