FROM debian:latest
RUN apt-get -y update
RUN apt-get -y upgrade
RUN apt-get install nginx -y
COPY nginx/default.conf /etc/nginx/sites-available/default
EXPOSE 80 443
CMD ["service", "nginx", "start"]
CMD ["bash"]
