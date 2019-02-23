FROM docker-test.art.local/docker-framework:latest

MAINTAINER Mark Galpin markg@jfrog.com

ADD war/*.war /home/exec/apache-tomcat-8.5.24/webapps/swampup.war

CMD /bin/bash -c cd /home/exec; /home/exec/apache-tomcat-8.5.24/bin/catalina.sh run
