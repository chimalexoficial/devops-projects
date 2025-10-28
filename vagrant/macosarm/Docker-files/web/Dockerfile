FROM nginx:latest

# Adding some tags
LABEL "Project"="Vprofile"
LABEL "Author"="AS"

# Removing default conf first
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/default.conf
