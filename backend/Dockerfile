FROM node:14

WORKDIR /asset

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5432

CMD ["node", "backendApp.js"]

