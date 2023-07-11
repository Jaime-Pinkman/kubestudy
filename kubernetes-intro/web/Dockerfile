# Use Nginx image from Docker Hub as the base image
FROM nginx:alpine

# Set the work directory
WORKDIR /app

# Copy your custom nginx.conf file into the Docker image
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expose port 8000 for the app
EXPOSE 8000

# Start Nginx when the Docker container is run
CMD ["nginx", "-g", "daemon off;"]
