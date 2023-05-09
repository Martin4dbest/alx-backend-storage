FROM ubuntu:18.04

# Install MongoDB
RUN apt-get update && apt-get install -y mongodb

# Create a data directory for MongoDB
RUN mkdir -p /data/db

# Expose the MongoDB port
EXPOSE 27017

# Start MongoDB when the container starts
CMD ["mongod"]

