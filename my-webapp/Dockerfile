FROM openjdk:8-jdk-alpine
WORKDIR /app
COPY target/my-webapp.war /app/my-webapp.war
RUN echo "This is a Docker Build Jenkins Step" > out.txt
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "my-webapp.war"]