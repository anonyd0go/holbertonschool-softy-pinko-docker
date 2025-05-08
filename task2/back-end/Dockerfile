FROM ubuntu:latest

# Update and install Python3, pip3
RUN apt-get update -y && apt-get upgrade -y && \
    apt-get install -y python3 python3-pip

# Install Flask using pip3
RUN pip3 install flask

# Set the working directory
WORKDIR /app

# Copy the Python file to the Docker image
COPY . /app

# Expose port 5252
EXPOSE 5252

# Command to run the application
CMD ["python3", "app.py"]
