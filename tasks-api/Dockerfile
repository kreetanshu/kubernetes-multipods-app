FROM node:23-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8000

RUN mkdir tasks

CMD [ "node", "tasks-app.js" ]