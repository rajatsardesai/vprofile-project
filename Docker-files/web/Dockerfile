#####################################################
# REPLACE DEFAULT NGINX CONF FILE WITH THE LATEST
#####################################################

FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Rajat"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
