FROM python:3.9-slim

# Set the working directory to /app
WORKDIR /app

# Copy the requirements file
COPY requirements.txt /app/

# Install the dependencies
RUN pip install -r requirements.txt

# Copy the application code
COPY requirements.txt /app/

# Expose the port
EXPOSE 5000

# Run the command to start the development server
CMD ["flask", "run", "--host=0.0.0.0"]