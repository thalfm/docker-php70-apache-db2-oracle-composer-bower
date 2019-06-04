FROM node:8.16.0-alpine

RUN apk add --no-cache git

RUN npm install -g bower

RUN bower -allow-root cache clean

CMD ["bower", "--allow-root", "install"]