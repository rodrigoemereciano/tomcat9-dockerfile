FROM tomcat:9.0.16-jre8

COPY conf/tomcat-users.xml conf/tomcat-users.xml
COPY conf/manager.xml conf/Catalina/localhost/manager.xml

RUN apt-get install tzdata -y && ln -fs /usr/share/zoneinfo/America/Recife /etc/localtime \ 
&& dpkg-reconfigure -f noninteractive tzdata



