FROM fedora:21

MAINTAINER dockerlite@gmail.com

RUN yum -y install yum-plugin-ovl
RUN yum -y update
RUN yum  -y install puppet hostname git unzip wget   && \
    yum clean all

RUN export TERM=xterm

CMD ["/sbin/init"]
