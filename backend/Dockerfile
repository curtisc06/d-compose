FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 90

CMD [ "npm", "start" ] 