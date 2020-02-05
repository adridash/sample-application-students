FROM openjdk:11-jre
COPY /home/travis/build/adridash/sample-application-students/sample-application-http-api-server/target/sample-application-http-api-server-0.0.1-SNAPSHOT.jar /home/travis/build/adridash/sample-application-students/sample-application-http-api-server/myapp.jar
EXPOSE 8091
ENTRYPOINT java -jar myapp.jar