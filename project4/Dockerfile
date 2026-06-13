# Phase 1: The Blueprint
FROM node:18-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy your local application files into the container
COPY src/ ./src

# Expose the internal container port to the outside world
EXPOSE 8080

# Command to execute your application
CMD ["node", "src/app.js"]
