# This is how to start this docker

docker run --name nginx -v /opt/ifw_content/assets:/usr/share/nginx/html:ro -p 8082:80 -d feitian/nginx