FROM haproxy:1.8.4-alpine
MAINTAINER David Papp <david@recart.com>

RUN apk add --no-cache \
        curl \
        bash

ADD haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg
EXPOSE 6379 6380

