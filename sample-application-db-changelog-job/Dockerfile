FROM openjdk:11-jre
COPY /home/travis/build/adridash/sample-application-students/sample-application-db-changelog-job/target/*.jar /home/travis/build/adridash/sample-application-students/sample-application-db-changelog-job/myapp.jar
EXPOSE 8090
ENTRYPOINT java -jar myapp.jar