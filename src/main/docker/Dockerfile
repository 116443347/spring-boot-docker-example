FROM java:8u111
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} app.jar
#ADD docker-spring-boot-1.0.0.jar app.jar
#RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]