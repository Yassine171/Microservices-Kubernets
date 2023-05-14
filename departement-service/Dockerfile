FROM eclipse-temurin:17-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} departement-service.jar
ENTRYPOINT ["java", "-jar","/departement-service.jar"]
EXPOSE 9002