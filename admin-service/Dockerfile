FROM adoptopenjdk/openjdk11
VOLUME /tmp
ADD target/admin-service.jar admin-service.jar
 ENTRYPOINT ["java","-jar","/admin-service.jar"]
