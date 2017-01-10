FROM fedora:20

MAINTAINER thijs.schnitger@container-solutions.com


RUN rpm -ivh http://yum.puppetlabs.com/puppetlabs-release-fedora-20.noarch.rpm && \
    yum -y install puppet hostname git unzip epel-release nano  && \
    yum clean all

RUN export TERM=xterm

CMD ["/sbin/init"]
