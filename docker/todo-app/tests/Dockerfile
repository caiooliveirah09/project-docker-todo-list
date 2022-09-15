FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD ./node_modules.tar.gz /app

COPY . /app

EXPOSE 3000

CMD ["npm", "test"]
