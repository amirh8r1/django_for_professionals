# Pull base image
FROM python:3.8

# Set environment variables
ENV PIP_DISABLE_PIP_VERSION_CHECK 1
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set work directory
WORKDIR /django_for_professionals

# Install dependencies
COPY ./requirements.txt .
RUN pip3 install -r requirements.txt

# Copy project
COPY . .