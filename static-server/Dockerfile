FROM node:8.9.3-alpine
LABEL maintainer="duxiaodong@darlin.me" version="1.1.0"

RUN npm i serve -g
VOLUME ["/resources"]
EXPOSE 8080
CMD ["serve", "--port", "8080", "/resources"]
