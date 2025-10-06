FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
ADD https://raw.githubusercontent.com/iam-veeramalla/Docker-Zero-to-Hero/refs/heads/main/README.md /usr/share/nginx/html/index.html
RUN chmod 755 /usr/share/nginx/html/index.html
ADD sample.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]