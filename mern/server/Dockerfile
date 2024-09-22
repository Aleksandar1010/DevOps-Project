FROM node:20.10-alpine3.19
WORKDIR /app
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 5050
CMD npm start