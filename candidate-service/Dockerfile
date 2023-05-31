FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/cadidate-service.jar cadidate-service.jar
ENTRYPOINT ["java","-jar","/cadidate-service.jar"]
