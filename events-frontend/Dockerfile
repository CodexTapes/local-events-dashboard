# Base Image
FROM node:slim

RUN mkdir /src/app

WORKDIR /src/app

COPY package*.json /src/app

COPY . /src/app

RUN npm install

RUN npm serve

EXPOSE 8080

