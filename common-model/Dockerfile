FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/common-model.jar common-model.jar
ENTRYPOINT ["java","-jar","/common-model.jar"]
