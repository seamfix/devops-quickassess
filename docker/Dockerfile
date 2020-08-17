FROM node:10

MAINTAINER devops@seamfix.com
RUN mkdir /var/app/
WORKDIR /var/app/
COPY target/*-thorntail.jar /opt/

EXPOSE 8081

ENTRYPOINT ["java", "-jar", "/opt/assessment-thorntail.jar"]