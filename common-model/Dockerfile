FROM adoptopenjdk/openjdk11
VOLUME /tmp
ADD target/common-model.jar common-model.jar
ENTRYPOINT ["java","-jar","/common-model.jar"]
