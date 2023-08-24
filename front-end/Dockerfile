FROM node:16.14-alpine

WORKDIR /front-end

EXPOSE 3070

COPY . .

RUN npm install

CMD ["npm", "run", "dev"]