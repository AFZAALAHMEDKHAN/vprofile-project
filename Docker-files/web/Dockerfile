FROM nginx
LABEL "Project"="vprofile"
LABEL "Author"="Afzaal"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginxvproapp.conf /etc/nginx/conf.d/nginxvproapp.conf
#this is a change