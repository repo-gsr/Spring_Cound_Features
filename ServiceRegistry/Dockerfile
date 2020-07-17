FROM maven:3.5.4-jdk-8

LABEL maintainer="subbareddygangalal@gmail.com"

EXPOSE 8081-8086

COPY target/ServiceRegistry-*.jar ServiceRegistry.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/ServiceRegistry.jar"]
