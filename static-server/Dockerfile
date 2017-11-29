FROM node:8.9.1-alpine
LABEL maintainer="duxiaodong@darlin.me" version="1.0.1"

RUN npm i http-server -g
VOLUME ["/resources"]
CMD ["http-server", "/resources"]
