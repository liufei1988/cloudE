FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD cloudE-turbine-server-1.0.0.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
