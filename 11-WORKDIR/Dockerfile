FROM almalinux:9
RUN mkdir /tmp/workdir-demo 
# RUN cd /tmp/workdir-demo   run command doesnot take you to the directory we need to use WORKDIR
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo "Hello, Iam in workdir" > hello.txt
CMD ["sleep", "1000"]