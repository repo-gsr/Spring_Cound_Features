FROM maven:3.5.4-jdk-8

LABEL maintainer="subbareddy@gmail.com"

EXPOSE 4007

COPY target/AdminConsole-*.jar AdminConsole.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/AdminConsole.jar"]
