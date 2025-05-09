FROM nginx:latest

# Copy the front-end files to the Nginx default directory
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy nginx config file to the app default config directory
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

# Expose port 80 for the web server
EXPOSE 9000