FROM java:8

EXPOSE 8999

ADD  target/api-gateway.jar api-gateway.jar

ENTRYPOINT [ "java" ,"-jar","api-gateway.jar"]