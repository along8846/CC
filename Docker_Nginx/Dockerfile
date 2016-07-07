# Nodejs
FROM nginx
MAINTAINER zhiwei.chen@feitian-tech.com

COPY default.conf /etc/nginx/conf.d/default.conf

VOLUME ["/var/cache/nginx"]

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]