FROM node:16.13.0

WORKDIR /website

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "start" ]