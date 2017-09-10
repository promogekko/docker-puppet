FROM centos:7
MAINTAINER thijs.schnitger@container-solutions.com


RUN rpm -ivh http://yum.puppetlabs.com/puppetlabs-release-el-7.noarch.rpm && \
    yum -y install puppet-server hostname tar git wget unzip nano && \
    yum clean all
 
RUN export TERM=xterm

EXPOSE 8140

ENTRYPOINT ["/sbin/init"]
#CMD puppet master --verbose --no-daemonize

