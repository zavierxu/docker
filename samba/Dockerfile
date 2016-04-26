FROM yikyo/base-alpine:latest

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk add --update samba && rm -rf /var/cache/apk/*

ADD smb.conf /etc/samba

EXPOSE 137/udp 138/udp 139/tcp 445/tcp

VOLUME ["/home/workspace"]

ENTRYPOINT ["smbd", "--foreground", "--log-stdout"]
