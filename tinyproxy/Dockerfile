FROM alpine:latest

MAINTAINER anjun <anjunact@qq.com>

ADD bootstrap.sh /etc/bootstrap.sh

RUN apk add --no-cache tinyproxy

ENTRYPOINT ["/etc/bootstrap.sh"]
