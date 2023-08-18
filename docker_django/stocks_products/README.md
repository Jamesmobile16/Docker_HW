docker build -t docker_django:1.0 .
docker run -it -p 8000:8000 docker_django:1.0
browse 127.0.0.1:8000/api/v1/
