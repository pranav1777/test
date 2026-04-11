FROM eclipse-temurin:17-jdk
WORKDIR /test
COPY target/*.jar test.jar
EXPOSE 8080
ENTRYPOINT [ "java","-jar","test.jar"]