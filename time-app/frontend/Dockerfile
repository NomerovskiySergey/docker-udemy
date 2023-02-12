FROM node:alpine

WORKDIR /app

EXPOSE 9000

COPY package*.json ./

RUN npm install

COPY . ./

CMD ["npm", "run", "dev"]