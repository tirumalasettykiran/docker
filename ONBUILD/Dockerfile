FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
#whoever uses this image as base image, these instructions will be executed in their build time, index.html needs to be present in their context
ONBUILD COPY index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]