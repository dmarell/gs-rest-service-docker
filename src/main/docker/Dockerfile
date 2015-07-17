# docker build -t gs-rest-service-docker .
# docker run -it --rm -p 8080:8080 -v /dev/urandom:/dev/random gs-rest-service-docker
#FROM tomcat:7
#COPY gs-rest-service-docker-${project.version}.war /usr/local/tomcat/webapps/gs-rest-service-docker.war

FROM java:8-jre
COPY ["gs-rest-service-docker-${project.version}.jar", "/gs-rest-service-docker.jar"]
CMD ["java", "-jar", "gs-rest-service-docker.jar"]
