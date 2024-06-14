# Use an official OpenJDK runtime as a parent image
FROM openjdk:18-jdk

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from the host to the container
COPY target/Hospital-Management-System-0.0.1-SNAPSHOT.jar app.jar

# Expose the application port
EXPOSE 8080

# Run the JAR file
ENTRYPOINT ["java", "-jar", "app.jar"]
