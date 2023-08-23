FROM node:16.14-alpine

WORKDIR /app/back-end

EXPOSE 3071

COPY . .

RUN npm install

CMD ["npm", "run", "dev"]