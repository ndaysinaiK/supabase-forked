# Use a base image
FROM docker.io/library/alpine:latest

# Install necessary dependencies
RUN apk --no-cache add wget

# Set the working directory
WORKDIR /app

# Copy the Docker Compose file
COPY . .

EXPOSE 4000 5000 8000 8080 8443 9999

CMD ["docker-compose", "up"]
