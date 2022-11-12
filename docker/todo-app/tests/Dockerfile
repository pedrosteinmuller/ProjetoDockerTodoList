FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app/user
ADD ./node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]