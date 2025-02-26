# Use an official OpenJDK runtime as a parent image
FROM openjdk:latest

# Set the working directory
WORKDIR /app

# Copy the JAR file into the container
COPY target/hello-world-1.0-SNAPSHOT.jar /app/hello-world.jar

# Expose port 8080 (if your application uses a web server)
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "hello-world.jar"]
