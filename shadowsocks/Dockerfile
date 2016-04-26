FROM alpine:3.3

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk add --update py-pip && rm -rf /var/cache/apk/*

RUN pip install shadowsocks

ENV SS_SERVER_ADDR 0.0.0.0
ENV SS_SERVER_PORT 8388
ENV SS_PASSWORD password
ENV SS_METHOD aes-256-cfb
ENV SS_TIMEOUT 300

EXPOSE $SS_SERVER_PORT

ENTRYPOINT ["/usr/bin/ssserver", "-s", "${SERVER_ADDR}", "-p", "${SERVER_PORT}", "-m", "${METHOD}", "-t", "${TIMEOUT}"]