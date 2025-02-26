FROM node:lts-alpine as build-stage

WORKDIR /feb22/frontend

COPY package*.json ./

COPY . .

RUN npm run build

EXPOSE 8080

CMD [ "npm", "run", "serve" ]