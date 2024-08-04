# Use the official Nginx image as the base image
FROM nginx:latest

# Remove the default Nginx welcome page
RUN rm /usr/share/nginx/html/index.html

# Copy the HTML file to the default Nginx HTML location
COPY index.html /usr/share/nginx/html/

# Copy the images to the default Nginx HTML location
COPY images/ /usr/share/nginx/html/images/

# Expose port 80
EXPOSE 80
