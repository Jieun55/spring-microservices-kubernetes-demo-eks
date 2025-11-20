FROM openjdk:26-ea-17-jdk-slim
COPY target/*.jar service.jar
CMD java ${JAVA_OPTS} -jar service.jar
