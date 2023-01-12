FROM openjdk:11-jre-slim
RUN mkdir /opt/app
COPY target/UserCrud.jar /opt/app/app.jar
CMD ["java", "-jar", "/opt/app/app.jar"]