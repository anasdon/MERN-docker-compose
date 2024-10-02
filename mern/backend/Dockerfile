FROM node:20.5.0-alpine

WORKDIR /app

COPY package.json .

RUN npm install -g npm@10.8.3

COPY . .

EXPOSE 5050

CMD ["npm", "start"]

