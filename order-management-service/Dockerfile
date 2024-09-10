FROM node:18-alpine

RUN apk add --no-cache bash

WORKDIR /app

RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm", "run", "start"]