FROM node:alpine

WORKDIR /usr/nodeApp

COPY ./package.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]
