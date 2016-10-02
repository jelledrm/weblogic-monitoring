FROM java:8
VOLUME /tmp
ADD weblogic-monitoring.jar weblogic-monitoring.jar
RUN sh -c 'touch /weblogic-monitoring.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/weblogic-monitoring.jar"]