FROM yikyo/base-alpine:latest

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk add --update nodejs git && rm -rf /var/cache/apk/*

RUN npm config set registry http://registry.cnpmjs.org

RUN npm install -g npm

ENTRYPOINT ["/bin/bash"]
