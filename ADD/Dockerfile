FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/daws-81s/dockerfiles/blob/main/FROM/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]