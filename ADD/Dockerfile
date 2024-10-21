FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/daws-81s/dockerfiles/blob/main/FROM/Dockerfile /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx","-g","daemon off;"]