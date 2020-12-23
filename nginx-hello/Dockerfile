FROM ubuntu:latest
CMD apt-get update -y
CMD apt-get install nginx -y

WORKDIR /app
COPY . .

CMD cp index.html /usr/share/nginx/html/
CMD cp default /etc/nginx/conf.d/

EXPOSE 80
