FROM node:14
WORKDIR /usr/app
ADD /node_modules.tar.gz ./
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
