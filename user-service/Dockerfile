FROM adoptopenjdk/openjdk11
VOLUME /tmp
ADD target/user-service.jar user-service.jar
ENTRYPOINT ["java","-jar","/user-service.jar"]
