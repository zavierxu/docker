FROM alpine:3.3

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk add --update bash && rm -rf /var/cache/apk/*

RUN echo "PS1=\"[\u@\h \W]\$ \"" > ~/.bashrc