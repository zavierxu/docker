FROM alpine:3.4

MAINTAINER zavierxu <zavierxu@gmail.com>

RUN apk add --update py-pip && rm -rf /var/cache/apk/*

RUN pip install shadowsocks

ENTRYPOINT ["/usr/bin/sslocal"]
