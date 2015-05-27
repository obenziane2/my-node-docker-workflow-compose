FROM node:latest

RUN mkdir /src

RUN npm install nodemon -g

WORKDIR /src
ADD . /src
RUN npm install

EXPOSE 3001

CMD npm start
