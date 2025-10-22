FROM openjdk:8u151-jdk-alpine3.7
EXPOSE 8070
ENV APP_HOME /usr/src/app
WORKDIR $APP_HOME
# Copy any JAR from target folder into the image
COPY target/*.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
