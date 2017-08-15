FROM ubuntu:14.04

MAINTAINER zhonglingyan "lyzhong@126.com"


COPY  1.txt /etc/1.txt
COPY  2.txt /etc/2.txt
COPY  entry.sh /entry.sh

RUN chmod 755 /entry.sh

ENTRYPOINT ["/entry.sh"]

