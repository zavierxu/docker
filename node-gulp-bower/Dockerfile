FROM yikyo/node:latest

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk add --update git && rm -rf /var/cache/apk/*

RUN npm install -g gulp bower

ENTRYPOINT ["/bin/bash"]