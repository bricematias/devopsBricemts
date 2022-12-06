Question 1:
docker pull alpine
docker build -t some-content-nginx .
docker run --name some-nginx -d some-content-nginx

docker run nginx
docker volume create volume-test
docker volume ls
docker volume inspect volume-test
docker run --name nginx -v ${pwd}/html:/usr/share/nginx/html -d -p 4300:80 nginx
docker run --name some-nginx -d -p 8080:80 some-content-nginx
docker images

        