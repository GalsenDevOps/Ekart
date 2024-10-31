# Use a more secure and recent base image
FROM openjdk:17-jdk-alpine

# Expose the port
EXPOSE 8070

# Set the working directory
WORKDIR /usr/src/app

# Copy the JAR file
COPY target/shopping-cart-0.0.1-SNAPSHOT.jar app.jar

# Set the entrypoint
ENTRYPOINT ["java", "-jar", "app.jar"]
