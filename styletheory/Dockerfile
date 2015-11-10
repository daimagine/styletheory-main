FROM node:onbuild

RUN mkdir /code
WORKDIR /code/styletheoryapi

COPY . /code/

RUN npm install

RUN sails lift