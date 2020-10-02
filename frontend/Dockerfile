FROM node:alpine as build
WORKDIR /app
ENV PORT=80
COPY package.json ./
COPY package-lock.json ./
RUN npm install --silent
COPY . ./
ENTRYPOINT npm start