FROM node:18-alpine


RUN apk add --no-cache bash curl

WORKDIR /app

RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm", "run", "start"]