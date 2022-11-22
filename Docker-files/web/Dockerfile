FROM nginx
LABEL "Project"="Multi-tier"
LABEL "Author"="Bharath"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
