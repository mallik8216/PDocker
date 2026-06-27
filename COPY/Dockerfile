FROM almalinux:9
RUN  dnf install -y nginx
CMD [ "nginx","-g", "daemon off;" ]
RUN rm -rf /usr/share/html/index.html
COPY index.html /usr/share/html/index.html