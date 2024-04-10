# Use a base image
FROM docker.io/library/alpine:latest

# Install necessary dependencies
RUN apk --no-cache add wget

# Set the working directory
WORKDIR /app

# Copy the Docker Compose file
COPY . .

CMD ["docker-compose", "up"]
