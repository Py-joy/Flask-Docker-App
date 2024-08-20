# Use an official Python runtime as the base image
FROM python:3.6

# Set the working directory in the container
WORKDIR /app

# Copy the requirements file into the container
COPY requirements.txt ./

# Install the Python dependencies
RUN pip install -r requirements.txt

# Copy the rest of the application code into the container
COPY . /app

# Expose the port that the application will run on
#EXPOSE 5000

# Define environment variable
#ENV FLASK_APP=app.py

# Set the command to run the application
CMD ["python", "app.py"]