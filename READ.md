

docker build -t hello_world_python -f Dockerfile .
docker run -d -p 6553:80 --name mybestwebsite hello_world_python:latest
curl 127.0.0.0:6553