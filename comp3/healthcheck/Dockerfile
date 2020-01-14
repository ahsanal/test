FROM ubuntu
RUN apt-get -y update && apt-get -y upgrade
RUN apt-get -y install nginx
EXPOSE 80
RUN apt-get -y install curl
CMD /usr/sbin/nginx -g 'daemon off;'
