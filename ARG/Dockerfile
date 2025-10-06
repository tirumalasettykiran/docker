ARG version
FROM almalinux:${version:-9}
ARG name = "Kiran" \
    company = "TCS" 
ENV NAME=$name
RUN echo "Hello $NAME from $company version is ${version}"
CMD ["sleep", "100"]  