FROM openjdk:jre-alpine
​
COPY target/*-thorntail.jar /opt/assessment-thorntail.jar
​
EXPOSE 8080
​
ENTRYPOINT ["java", "-jar", "/opt/assessment-thorntail.jar"]