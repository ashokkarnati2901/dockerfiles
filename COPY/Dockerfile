FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY projects /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]