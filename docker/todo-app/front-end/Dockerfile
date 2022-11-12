FROM node:14
EXPOSE 3000
WORKDIR /usr/app
ADD ./node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]