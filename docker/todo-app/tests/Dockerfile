FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /
COPY package*.json ./
RUN npm install
COPY . .
ENTRYPOINT ["npm", "test"]

