FROM node:14.16.0-alpine3.10

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8085

CMD ["node", "app.js"]


