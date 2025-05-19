FROM nginx:latest

LABEL Project="Vprofile"
LABEL Author="Rahul"

# Remove default site configuration
RUN rm -f /etc/nginx/conf.d/default.conf

# Copy your custom config
COPY nginvproapp.conf /etc/nginx/conf.d/nginvproapp.conf

