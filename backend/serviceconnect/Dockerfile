FROM openjdk:17-oracle
LABEL authors="sathu"

ARG JAR_FILE= /target/serviceconnect-0.0.1-SNAPSHOT.jar

COPY ${JAR_FILE} serviceconnect.jar

ENTRYPOINT [ "java","-jar","/serviceconnect.jar" ]