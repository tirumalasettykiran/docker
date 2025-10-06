FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
ADD https://github.com/iam-veeramalla/Docker-Zero-to-Hero/blob/main/README.md /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
ADD sample.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]