FROM node:current-slim
EXPOSE 8080

WORKDIR /usr/src/app
COPY package.json .
RUN npm install

CMD [ "npm", "start" ]

COPY . .
