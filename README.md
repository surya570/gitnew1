FROM ubuntu
RUN  apt-get update &&  apt-get install apache2 -y
CMD ["echo","This is Devil"]
