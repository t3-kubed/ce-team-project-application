FROM node:18.12.1-alpine as build
WORKDIR /app
COPY package.json .
RUN npm i
COPY . .
EXPOSE 80
CMD ["npm", "run", "dev"]