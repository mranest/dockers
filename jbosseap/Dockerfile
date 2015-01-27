# DOCKER-VERSION 1.2.0
FROM mranest/oracle_jdk

ADD ./jboss-eap-6.3.2.tgz /usr/share/

EXPOSE 9999
EXPOSE 9990
EXPOSE 9443

EXPOSE 8009
EXPOSE 8080
EXPOSE 8443
EXPOSE 4447
EXPOSE 4712
EXPOSE 4713

#CMD /usr/share/jboss-eap-6.3/bin/standalone.sh -b 0.0.0.0
ENTRYPOINT ["/usr/share/jboss-eap-6.3/bin/standalone.sh"]
CMD ["-b", "0.0.0.0"]
