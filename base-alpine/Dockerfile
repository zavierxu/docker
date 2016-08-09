FROM alpine:3.3

MAINTAINER yikyo <yikyo666@gmail.com>

RUN sed -i '1i\http://mirrors.ustc.edu.cn/alpine/v3.3/main/' /etc/apk/repositories

RUN apk add --update bash && rm -rf /var/cache/apk/*

RUN echo "PS1=\"[\u@\h \W]\$ \"" > ~/.bashrc