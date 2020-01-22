FROM java:8
MAINTAINER kpioneer123 kpioneer
VOLUME /home/kpioneer123
ADD docker-0.0.1-SNAPSHOT.jar app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]