FROM node:14-alpine

WORKDIR /app

ADD ./node_modules.tar.gz /app

COPY . /app

EXPOSE 3001

CMD ["npm", "start"]
