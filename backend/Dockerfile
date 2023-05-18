# Base image
FROM openjdk:11-jdk-slim

# Set the working directory
WORKDIR /app

# Copy the application JAR file
COPY target/studentsystem-0.0.1-SNAPSHOT.jar /app/studentsystem-0.0.1-SNAPSHOT.jar

# Expose port 8080
EXPOSE 8080

# Set the entrypoint command
CMD ["java", "-jar", "/app/studentsystem-0.0.1-SNAPSHOT.jar"]