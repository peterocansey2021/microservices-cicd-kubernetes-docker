# syntax=docker/dockerfile:1

FROM node:12.18.1

ENV NODE_ENV=production

WORKDIR /app/heroes_service

COPY . /app/heroes_service

RUN npm install --production

#COPY . /app/heroes_service

EXPOSE 8081

CMD [ "node", "heroes.js" ]