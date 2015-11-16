FROM node:latest

RUN mkdir /code
WORKDIR /code/styletheoryapi

COPY . /code/

RUN apt-get update &&\
    apt-get -y upgrade &&\
    apt-get -y install nodejs nodejs-legacy nodejs-dev npm git curl

RUN npm cache clean
#RUN npm install

CMD ["sails lift"]