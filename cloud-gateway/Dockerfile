FROM eclipse-temurin:17-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} cloud-gateway-service.jar
ENTRYPOINT ["java", "-jar","/cloud-gateway-service.jar"]
EXPOSE 9002