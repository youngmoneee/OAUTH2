FROM openjdk:11-jdk-slim

EXPOSE 3040
COPY ./target/auth.jar auth.jar
ENTRYPOINT ["java", "-jar", "./auth.jar"]
