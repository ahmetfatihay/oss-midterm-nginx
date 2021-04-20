sudo docker build -t nginxserver .
docker run -d -p 80:80 nginxserver
docker rm -f $(docker ps -aq)