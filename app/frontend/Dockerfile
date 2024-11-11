FROM node:16.19.0-alpine

WORKDIR /app-frontend

COPY . .

RUN npm install

RUN npm run build

CMD ["npm", "start"]
