# Use a basic Nginx image as a parent image
FROM nginx:alpine

# Copy the custom Nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the static content of the frontend
COPY . /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80
