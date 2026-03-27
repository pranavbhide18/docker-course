FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

# since we have a workdir then everything will run relative to that. Without it in copy we would run . /app
# but not we can COPY . ./
COPY . /app


EXPOSE 80

CMD ["node", "server.js"]