FROM almalinux:8
RUN yum imstall nginx -y
RUN rm -f /usr/share/nginx/html/index.html
COPY projects /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon-off;"]