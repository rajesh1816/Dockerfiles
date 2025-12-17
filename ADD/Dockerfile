FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#ADD https://github.com/daws-84s/notes/blob/main/demo.txt /usr/share/nginx/html/index.html
ADD sample-1.tar /usr/share/nginx/html/
RUN chmod +r /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]
