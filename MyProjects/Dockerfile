FROM ubuntu
RUN apt-get update -y
RUN apt-get install -y apache2
RUN apt-get install -y apache2-utils
ENTRYPOINT ["apache2ctl"]
CMD ["-DFOREGROUND"]
