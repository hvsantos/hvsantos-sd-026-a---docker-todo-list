FROM node:14-alpine

EXPOSE 3000

WORKDIR /frontend

ADD ./node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]