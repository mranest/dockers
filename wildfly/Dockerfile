# DOCKER-VERSION 1.2.0
FROM mranest/oracle_jdk

MAINTAINER Anestis Georgiadis <mranest@gmail.com>

ADD ./wildfly-8.2.0.Final.tar.gz /usr/share/

EXPOSE 8080
EXPOSE 9990

#CMD /usr/share/wildfly-8.2.0.Final/bin/standalone.sh -b 0.0.0.0
ENTRYPOINT ["/usr/share/wildfly-8.2.0.Final/bin/standalone.sh"]
CMD ["-b", "0.0.0.0"]
