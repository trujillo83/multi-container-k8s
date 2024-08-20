# frontend/Dockerfile
FROM node:16-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install -g express

COPY . .

EXPOSE 80

CMD ["npm", "start"]
