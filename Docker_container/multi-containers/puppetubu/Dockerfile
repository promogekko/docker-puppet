FROM ubuntu:latest

MAINTAINER thijs.schnitger@container-solutions.com


# Install system dependencies

# si a cause d'un probleme selinux  taper cette commande ci-dessous  dans une console shell ( place ici pour memoire)
# mount -o remount,ro /sys/fs/selinux

RUN apt-get -y update && apt-get -y install git wget tar puppet nano upstart

RUN export TERM=xterm

CMD ["/sbin/init"]
