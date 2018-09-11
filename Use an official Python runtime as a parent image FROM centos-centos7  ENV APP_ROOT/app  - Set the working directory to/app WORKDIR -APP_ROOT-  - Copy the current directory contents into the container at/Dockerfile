# Use an official Python runtime as a parent image
FROM centos:centos7

ENV APP_ROOT /app

# Set the working directory to /app
WORKDIR "${APP_ROOT}"

# Copy the current directory contents into the container at /app
ADD . "${APP_ROOT}"	

# Install prerequisites
RUN \
    yum update -y; \
    yum install epel-release -y; \
    yum install -y wget python-pip 
