FROM node:0.10.38

RUN mkdir -p /src/app
ADD . /src/app
WORKDIR /src/app
RUN npm install
EXPOSE  9000

CMD node server.js
