FROM ubuntu

WORKDIR /etc/init.d

RUN apt-get update && apt-get install -y nginx

CMD ["sh", "-c", "./nginx start && tail -f /dev/null"]