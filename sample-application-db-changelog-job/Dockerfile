FROM openjdk:11-jre
COPY ./sample-application-db-changelog-job/target/sample-application-db-changelog-job-0.0.1-SNAPSHOT-exec.jar ./sample-application-db-changelog-job/myapp.jar
EXPOSE 8090
ENTRYPOINT java -jar myapp.jar