# Stage 1: Build the application
# Use an official Java 8 runtime as a parent image
FROM openjdk:8-jre-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the Spring Boot JAR file (replace 'your-app.jar' with your actual JAR file)
COPY target/springboot-backend-1.0.jar /app/app.jar

# Expose the port that your Spring Boot application listens on (e.g., 8080)
EXPOSE 8080

# Define the command to run your Spring Boot application
CMD ["java", "-jar", "app.jar"]
