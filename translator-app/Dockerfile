# Use the official Python image as a base image
FROM python:3.8

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed dependencies specified in requirements.txt
RUN pip install -r requirements.txt

# Expose the port the app runs on
EXPOSE 5000

# Run app.py when the container launches
CMD ["python", "app.py"]
