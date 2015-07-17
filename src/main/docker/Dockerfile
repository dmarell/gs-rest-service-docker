# docker build -t gs-rest-service-docker-war .
# docker run -it --rm -p 8080:8080 -v /dev/urandom:/dev/random gs-rest-service-docker-war
FROM tomcat:7
COPY gs-rest-service-docker-war-${project.version}.war /usr/local/tomcat/webapps/gs-rest-service-docker-war.war
