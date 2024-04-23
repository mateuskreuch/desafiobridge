# Use a base image with Java pre-installed
FROM openjdk:18-jdk-slim

# Copy the packaged JAR file into the container at defined working directory
COPY PrimeCounter.jar app.jar

# Expose the port your application runs on
EXPOSE 8080

# Command to run the application when the container starts
ENTRYPOINT ["java", "-jar", "/app.jar"]
