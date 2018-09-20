FROM nginx:1.15.3

# Copy our custom configuration file into the docker container.
COPY nginx.conf /etc/nginx/nginx.conf
ADD sites-enabled /etc/nginx/sites-enabled/

# Expose ports for HTTP and HTTPS.
EXPOSE 80 443

