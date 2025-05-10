# Use an official OpenJDK runtime as the base image
FROM openjdk:21

# Set the working directory in the container
WORKDIR /app

# Copy the jar file into the container (adjust the filename if needed)

# Copy the jar file into the container (adjust the filename if needed)
COPY target/Train-0.0.1-SNAPSHOT.jar app.jar

# Expose port (same as in Spring Boot, default 8080)
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]