# Use Amazon Linux as the base image
FROM amazonlinux:latest

# Set the working directory inside the container
WORKDIR /app

# Copy a "Hello, World!" script into the container
COPY hello.sh .

# Set execute permissions for the script
RUN chmod +x hello.sh

# Define the command to run when the container starts
CMD ["./hello.sh"]

