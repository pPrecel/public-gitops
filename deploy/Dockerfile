FROM node:12.18.0-alpine3.12

RUN mkdir /app

WORKDIR /app

COPY code ./

USER node

RUN npm install

CMD [ "npm", "start" ]
