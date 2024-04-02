FROM almalinux:8
# alamlinux is same as centos
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
# deamon off command makes our container running and attached to screen
CMD [ "nginx", "-g", "daemon off;" ]