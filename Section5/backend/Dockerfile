FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . /app

ENV MONGODB_USERNAME=pranavbhide
ENV MONGDB_PASSWORD=secret

EXPOSE 80

CMD [ "npm", "start" ]