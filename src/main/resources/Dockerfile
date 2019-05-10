# Dockerfile
FROM openjdk:8-jdk-alpine

#SHELL ["/bin/bash", "-c"]

EXPOSE 8080
VOLUME /tmp
#ADD . /helloRest/
WORKDIR ./home


RUN ls -l

COPY /helloRest-1.0-SNAPSHOT.jar  app.jar
RUN ls -l

#CMD java - jar app.jar
#CMD java -version
CMD ["java", "-jar", "app.jar"]