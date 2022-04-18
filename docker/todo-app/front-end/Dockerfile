FROM node:14-alpine AS build
WORKDIR /
EXPOSE 3000
COPY package*.json ./
RUN npm install -s
COPY . .
ENTRYPOINT ["npm", "start"]
