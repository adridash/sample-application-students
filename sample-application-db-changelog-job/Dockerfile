FROM openjdk:11-jre
COPY $HOME/build/adridash/sample-application-students/sample-application-db-changelog-job/target/*.jar $HOME/build/adridash/sample-application-students/sample-application-db-changelog-job/myapp.jar
EXPOSE 8090
ENTRYPOINT java -jar myapp.jar