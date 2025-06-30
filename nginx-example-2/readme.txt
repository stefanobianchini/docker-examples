Esempio di Dockerfile con immagine iniziale Ubuntu sulla quale viene installato nginx

docker build -t nginx-example-2 .
docker run -d -p 8081:80 nginx-example-2