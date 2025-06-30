Esempio di Dockerfile per app react non ottimizzato:
docker build -f Dockerfile-no-multi -t react-wrong-attempt .
docker run -d -p 8082:80 react-wrong-attempt


Esempio di Dockerfile per app react ottimizzato (multi stage build):
docker build -t react-example .
docker run -d -p 8083:80 react-example