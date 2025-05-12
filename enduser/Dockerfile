FROM openjdk:25-oracle
WORKDIR /app
COPY target/spring-enduser.jar app.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "app.jar"]