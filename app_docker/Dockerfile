FROM openjdk:8
EXPOSE 8081
ADD ./app_docker-1.0-SNAPSHOT.jar /app_docker.jar
RUN bash -c 'touch /app_docker.jar'
ENTRYPOINT ["java","-jar","/app_docker.jar"]