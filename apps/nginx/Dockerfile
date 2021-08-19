FROM nginx:1.19.6

#RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y python-certbot-nginx \
#    vim cron gnupg1 procps sudo wget iputils-ping logrotate

COPY ./default.conf /etc/nginx/conf.d/
