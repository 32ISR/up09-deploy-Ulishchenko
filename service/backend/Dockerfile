FROM node:20-slim

WORKDIR /app

COPY package*.json ./

RUN npm ci

COPY . .

EXPOSE 300

CMD ["node", "index.js"]



