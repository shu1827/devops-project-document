FROM nginx
LABEL "project"="Containerization"
LABEL "Author"="shubham"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf
