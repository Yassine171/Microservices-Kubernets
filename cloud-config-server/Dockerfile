FROM eclipse-temurin:17-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} cloud-config-service.jar
ENTRYPOINT ["java", "-jar","/cloud-config-service.jar"]
EXPOSE 9002