FROM openjdk:8-jdk-slim

MAINTAINER devops@seamfix.com
WORKDIR /opt/
COPY target/*-thorntail.jar /opt/assessment-thorntail.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/opt/assessment-thorntail.jar"]