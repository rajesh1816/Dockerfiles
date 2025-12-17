FROM almalinux:9
RUN dnf install nginx -y
RUN useradd rajesh
USER rajesh
ENTRYPOINT [ "sleep" ]
CMD [ "1000" ]