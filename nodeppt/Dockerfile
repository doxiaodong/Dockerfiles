FROM node:8.9.3-alpine
LABEL maintainer="duxiaodong@darlin.me" version="1.0.0"

RUN npm i nodeppt -g
VOLUME ["/ppts"]
EXPOSE 8080
CMD ["nodeppt", "start", "-d", "/ppts"]
