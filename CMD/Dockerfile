FROM almalinux:8
# alamlinux is same as centos
RUN yum install nginx -y
RUN echo "Hello welcome to Dockerfile, A way of creating own image" > /usr/share/nginx/hello.html
# deamon off command makes our container running and attached to screen
CMD [ "nginx", "-g", "deamon off" ]