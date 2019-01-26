FROM debian:latest

LABEL maintainer="Johnny Sun <bmy001@gmail.com>"

ARG TZ='Aisa/Shanghai'

ENV TZ $TZ

RUN apt-get update \
    && yes | apt-get install shadowsocks-libev

ADD entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]

    
