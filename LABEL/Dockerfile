FROM almalinux:9
LABEL author="Kiran" \
    company="TCS" \
    description="This is a sample label image"
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]