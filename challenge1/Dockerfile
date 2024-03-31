# Use the Nginx image from Docker Hub
FROM nginx:alpine

# Copy the static content into the container
COPY ./public /usr/share/nginx/html

# Expose port 80 to the host machine
EXPOSE 80

# Start Nginx when the container has provisioned
CMD ["nginx", "-g", "daemon off;"]
