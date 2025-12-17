FROM almalinux:9
RUN dnf install nginx -y
RUN useradd rajesh
USER rajesh
CMD [ "nginx","-g","daemon off;" ]