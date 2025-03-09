# Use an official lightweight Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy all project files into the container
COPY . /app

# Install required dependencies
RUN pip install scikit-learn joblib

# Run the ML script when the container starts
CMD ["python", "ml-model.py"]
