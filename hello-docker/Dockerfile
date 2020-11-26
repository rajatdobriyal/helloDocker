FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD hello-docker-0.0.1-SNAPSHOT.jar hello-docker-app.jar
EXPOSE 9080
ENTRYPOINT ["java", "-jar", "hello-docker-app.jar"]