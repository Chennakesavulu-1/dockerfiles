FROM almalinux:8
# alamlinux is same as centos
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/hello.html
RUN echo "Hello welcome to Dockerfile, A way of creating own image" > /usr/share/nginx/html/hello.html
# deamon off command makes our container running and attached to screen
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]


# FROM run:v1
# RUN echo "Hello, welcome to Dockerfile. A way of creating own images." > /usr/share/nginx/html/hello.html
# daemon off command makes our container running and attached to screen
# CMD [ "nginx", "-g", "daemon off;" ]