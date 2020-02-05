FROM openjdk:11-jre
COPY ./target/sample-application-db-changelog-job-0.0.1-SNAPSHOT-exec.jar ./myapp.jar
EXPOSE 8090
ENTRYPOINT java -jar myapp.jar