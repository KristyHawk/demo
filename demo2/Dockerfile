FROM openjdk:18-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} demo2.jar
ENTRYPOINT ["java", "-jar", "/demo2.jar"]