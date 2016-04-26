FROM alpine:3.3

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk add --update py-pip && rm -rf /var/cache/apk/*

RUN pip install shadowsocks

ENTRYPOINT ["/usr/bin/ssserver"]
