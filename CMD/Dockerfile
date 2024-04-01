FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello Nginx creating own image" > /usr/share/nginx/hello.html
CMD [ "nginx", "-g", "daemon off;" ]