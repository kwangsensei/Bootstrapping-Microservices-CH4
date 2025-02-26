FROM nginx:latest

# Copy the SSL certificates (self-signed or created by you) to the container
COPY ./ssl/nginx.crt /etc/nginx/ssl/nginx.crt
COPY ./ssl/nginx.key /etc/nginx/ssl/nginx.key

# Copy the custom nginx.conf to replace the default one
COPY ./nginx.conf /etc/nginx/nginx.conf

# Expose port 80 and 443
EXPOSE 80 443
