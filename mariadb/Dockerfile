FROM debian:latest
RUN apt-get -y update
RUN apt-get -y upgrade
RUN apt-get install mariadb-server -y
RUN service mysql start
EXPOSE 8336
CMD ["bash"]