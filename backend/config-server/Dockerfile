# Use lightweight Java runtime
FROM eclipse-temurin:17-jre-alpine

WORKDIR /config-server

COPY target/config-server-0.0.1-SNAPSHOT.jar app.jar

CMD ["java","-jar","app.jar"]
