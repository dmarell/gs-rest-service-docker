# docker build -t gs-rest-service-docker .
# docker run -it --rm -p 8080:8080 -v /dev/urandom:/dev/random gs-rest-service-docker
#FROM tomcat:7
#COPY target/gs-rest-service-0.1.0.war /usr/local/tomcat/webapps/gs-rest-service.war

FROM java:8-jre
COPY target/gs-rest-service-docker-1.0.0-SNAPSHOT.jar /gs-rest-service-docker.jar
CMD ["java", "-jar", "gs-rest-service-docker.jar"]
