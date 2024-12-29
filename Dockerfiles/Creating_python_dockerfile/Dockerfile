# Use the official Python image as the base image
FROM python:latest

# Set the working directory in the container
WORKDIR /app

# Copy the requirements.txt file into the container
COPY requirements.txt .

# Install the dependencies listed in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code (app.py) into the container
COPY . .

# Expose port 5000 for the Flask application (or your chosen port)
EXPOSE 5000

# Use Gunicorn to serve the app (for production)
CMD ["gunicorn", "--bind", "0.0.0.0:5000", "app:app"]


