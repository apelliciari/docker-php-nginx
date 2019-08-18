# Docker PHP-FPM 5.6 & Nginx 1.10 on Alpine Linux

Build if needed:

    docker build -t alpine-phpfpm-nginx . 

Start the Docker container (in the folder):

    docker run -p 80:8080 trafex/alpine-phpfpm-nginx


PHP 5.6 version based on https://hub.docker.com/r/trafex/alpine-nginx-php7/

