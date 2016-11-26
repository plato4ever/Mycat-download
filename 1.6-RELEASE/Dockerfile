from openjdk:8-jdk
MAINTAINER zhaolp

#install mycat
VOLUME /opt/mycat/conf
ADD Mycat-server-1.6-RELEASE-20161028204710-linux.tar.gz /opt

EXPOSE 8066 9066
CMD ["/opt/mycat/bin/mycat","console"]
