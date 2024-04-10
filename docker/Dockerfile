# Use a base image
FROM docker.io/library/alpine:latest

# Install necessary dependencies
RUN apk --no-cache add wget

# Set the working directory
WORKDIR /app

# Copy the Docker Compose file
COPY docker-compose.yml ./

# Expose necessary ports
EXPOSE 4000 5000 8000 8080 8443 9999

# Define environment variables
ENV POSTGRES_PASSWORD=mysecretpassword
# Add other environment variables as needed

# Run commands to start the services
CMD ["docker-compose", "up"]
