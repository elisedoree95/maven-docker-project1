FROM openjdk:8
ADD target/my-maven-app-1.0-SNAPSHOT.jar my-maven-app-1.0-SNAPSHOT.jar
RUN echo "This is a docker Build Jenkins Step" > out.txt
ENTRYPOINT ["java", "-jar","my-maven-app-1.0-SNAPSHOT.jar"]
EXPOSE 8080