FROM maven:3.5.4-jdk-8

LABEL maintainer="me"

VOLUME /tmp

EXPOSE 4012

COPY target/ConfigServer-*.jar ConfigServer.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/ConfigServer.jar"]
