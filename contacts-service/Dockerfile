FROM java:8

EXPOSE 8282

ADD  target/contacts-service.jar contacts-service.jar

ENTRYPOINT [ "java" ,"-jar","contacts-service.jar"]