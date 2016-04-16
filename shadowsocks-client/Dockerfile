FROM alpine:3.3

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk update && apk add py-pip

RUN pip install shadowsocks

ENTRYPOINT ["/usr/bin/sslocal"]
