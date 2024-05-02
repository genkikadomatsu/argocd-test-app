# Use Amazon Linux as the base image
FROM amazonlinux:latest

# Set the working directory inside the container
WORKDIR /app

# Copy a "Hello, World!" script into the container
COPY goodbye.sh .

# Set execute permissions for the script
RUN chmod +x goodbye.sh

# Define the command to run when the container starts
CMD ["./goodbye.sh"]

