# Use the official OpenJDK image as the base image
FROM openjdk:17-oracle

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled Spring Boot JAR file into the container
COPY build/libs/producer-0.0.1-SNAPSHOT.jar producer.jar

# Expose the port specified in the application.properties
EXPOSE 8090

# Command to run the Spring Boot application
CMD ["java", "-jar", "producer.jar"]