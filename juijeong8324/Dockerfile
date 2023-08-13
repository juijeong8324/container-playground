FROM node:latest
MAINTAINER juijeong8324 juijeong8324@gmail.com

RUN mkdir -p /app
WORKDIR /app
ADD package*.json /app
RUN npm install --production
ADD . /app

EXPOSE 8080
CMD ["npm", "start"]