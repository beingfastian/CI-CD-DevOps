FROM node:latest
WORKDIR /app

COPY package*.json ./
RUN npm install --legacy-peer-deps --verbose

COPY . .
EXPOSE 3000
CMD ["npm", "start"]