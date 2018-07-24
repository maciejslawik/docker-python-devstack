FROM python:3.7.0

MAINTAINER Maciej Slawik <maciekslawik@gmail.com>

# Add new user
RUN useradd -ms /bin/bash user

# Set ID
RUN usermod -u 1000 user

# Set default work directory
WORKDIR /python

