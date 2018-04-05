FROM node:8.7-alpine

WORKDIR /usr/app

COPY package*.json ./
RUN npm install -qy

COPY . .

EXPOSE 8080

CMD ["npm", "start"]
