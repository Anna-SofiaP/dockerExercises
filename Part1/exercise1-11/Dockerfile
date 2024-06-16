FROM amazoncorretto:8

EXPOSE 8080

WORKDIR /usr/src/app

# Copy the source code
COPY /material-applications/spring-example-project .

# Build the project
RUN ./mvnw package

# Run the project with the command 'java -jar ./target/docker-example-1.1.3.jar'
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
