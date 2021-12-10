# syntax=docker/dockerfile:1
FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
# Set the working directory to /code.
WORKDIR /code
# Copy requirements.txt and install the Python dependencies.
COPY requirements.txt /code/
RUN pip install -r requirements.txt
# Copy the current directory . in the host machine to /code/ in the image.
COPY . /code/
