FROM node:8.9.1-alpine

ENV VERSION 1.0.0

RUN npm i http-server -g
VOLUME ["/resources"]
CMD ["http-server", "/resources"]
