# My nginx

## Build image

docker build -t nginx:xzx .

## Run image

docker run --name webserver -d -p 80:80 nginx:xzx
