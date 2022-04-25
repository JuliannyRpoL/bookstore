FROM node:14.18

RUN mkdir /app

WORKDIR /app

COPY package.json /app
RUN npm install

COPY . /app

EXPOSE 3000

ENTRYPOINT [ "npm", "run", "start" ]