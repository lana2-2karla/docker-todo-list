FROM node:14-alpine AS build
WORKDIR /
EXPOSE 3001
COPY package*.json ./
RUN npm install -s
COPY . .
ENTRYPOINT ["npm", "start"]