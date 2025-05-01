# Use the official Python image as a base image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any required Python packages
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 80 (you can change this depending on your app)
EXPOSE 80

# Define the command to run your application
CMD ["python", "main.py"]
