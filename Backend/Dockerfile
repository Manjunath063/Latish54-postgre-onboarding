FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

RUN mkdir -p /app/Uploads

EXPOSE 3094

CMD ["node", "server.js"]

