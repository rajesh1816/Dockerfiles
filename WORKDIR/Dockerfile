FROM almalinux:9
RUN mkdir /tmp/workdir-demo
WORKDIR /tmp/workdir-demo
RUN useradd rajesh
USER rajesh
RUN echo "hello i am from workdir -demo" > hello.txt
CMD [ "sleep", "1000" ]
