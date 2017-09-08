FROM fedora:25

MAINTAINER dockerlite@gmail.com

RUN dnf install -y http://yum.puppetlabs.com/fedora/f25/PC1/x86_64/puppet-agent-1.10.7-1.fedoraf25.x86_64.rpm && \
    yum -y install  hostname git unzip   && \
    yum clean all

RUN export TERM=xterm

CMD ["/sbin/init"]
