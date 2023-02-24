
FROM node:14-alpine

EXPOSE 3001

WORKDIR /backend

ADD ./node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]