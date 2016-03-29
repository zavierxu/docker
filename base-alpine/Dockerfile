FROM alpine:3.3

MAINTAINER yikyo <yikyo666@gmail.com>

RUN apk update && apk upgrade

RUN apk add bash

RUN echo "PS1=\"[\u@\h \W]\$ \"" > ~/.bashrc
