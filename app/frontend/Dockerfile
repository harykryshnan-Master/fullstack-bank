FROM node:16.20.1-alpine

WORKDIR /app-frontend

COPY . .

RUN npm install

RUN npm run build

CMD ["npm", "start"]
