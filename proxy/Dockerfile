# Version: 0.0.1
FROM haproxy:1.7
COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg 
MAINTAINER Dmitry Yevtushenko <dmitriy.yevtushenko@gmail.com>
RUN apt-get update
RUN apt-get install -y haproxy
EXPOSE 80
