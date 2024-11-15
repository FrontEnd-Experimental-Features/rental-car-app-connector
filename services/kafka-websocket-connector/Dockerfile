FROM openjdk:11-jre-slim

WORKDIR /app

# Copy the application jar file
COPY target/*.jar app.jar

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"] 