FROM almalinux:8
RUN yum install nginx -y
EXPOSE 80\tcp
# expose is not adding any functionality, this is for just information
CMD [ "nginx", "-g", "daemon off;" ]