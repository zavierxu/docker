FROM yikyo/base-alpine:latest

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk add --update nodejs git && rm -rf /var/cache/apk/*

RUN npm config set registry https://registry.npm.taobao.org

RUN npm install -g npm

ENTRYPOINT ["/bin/bash"]
