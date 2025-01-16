FROM openjdk:8
ADD target/my-maven-app.jar my-maven-app.jar
RUN echo "This is a docker Build Step" > out.txt
ENTRYPOINT ["java", "-jar","my-maven-app.jar"]
EXPOSE 8080