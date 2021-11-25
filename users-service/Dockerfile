FROM java:8

EXPOSE 8181

ADD  target/users-service.jar users-service.jar

ENTRYPOINT [ "java" ,"-jar","users-service.jar"]