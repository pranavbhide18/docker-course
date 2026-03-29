FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

# VOLUME ["/app/node_modules"] // add this volume to tell docker to not load node_modules from local bind mount

CMD ["npm", "start"]