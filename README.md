# nginx_test

docker build -t a4t/nginx_test .
docker run -p 8080:80 a4t/nginx_test
curl localhost:8080
