FROM ubuntu:20.04
RUN apt-get update
RUN apt-get install apache2 -y
COPY ./index.html /usr/share/apache2/index.html
CMD [ "apache2", "-DFOREGROUND" ]