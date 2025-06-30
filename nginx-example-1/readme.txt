Esempio di Dockerfile con nginx e comando ping

docker build -t nginx-example-1 .
docker run -d -p 8080:80 nginx-example-1