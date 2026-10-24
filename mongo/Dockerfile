# Use the official MongoDB base image
FROM mongo:7.0

# Optional: Set environment variables for default root user and password
ENV MONGO_INITDB_ROOT_USERNAME=admin
ENV MONGO_INITDB_ROOT_PASSWORD=123456

# Expose the default MongoDB port
EXPOSE 27017

# Expose volumes to persist database and configuration files
VOLUME ["/data/db", "/data/configdb"]

# The base image already has the ENTRYPOINT ["docker-entrypoint.sh"]
# and CMD ["mongod"]. No need to redefine them unless adding custom flags.

