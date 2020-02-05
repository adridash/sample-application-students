FROM openjdk:11-jre
COPY $HOME/build/adridash/sample-application-students/sample-application-http-api-server/target/*.jar $HOME/build/adridash/sample-application-students/sample-application-http-api-server/myapp.jar
EXPOSE 8091
ENTRYPOINT java -jar myapp.jar