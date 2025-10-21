# OrderService Dockerfile - Simple Version
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy the JAR file (make sure to build it first with mvn clean package)
COPY target/*.jar app.jar

# Expose port
EXPOSE 8082

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]