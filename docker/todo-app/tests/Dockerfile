FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /
COPY package*.json ./
RUN npm install -s
COPY . .
ENTRYPOINT ["npm", "test"]

