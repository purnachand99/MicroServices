FROM java:8u111-jre-alpine
MAINTAINER vaneetkataria54@gmail.com
COPY target/netflix-eureka-naming-server-0.0.1-SNAPSHOT.jar /App.jar
EXPOSE 8761
VOLUME /tmp
ENTRYPOINT ["java", "-jar" ,  "/App.jar"]

