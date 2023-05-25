FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 6500

CMD ["node", "server.js"]

