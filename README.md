# TastyIgniter Docker
[![Docker Pulls](https://img.shields.io/docker/pulls/toshsramen/tastyigniter)](https://hub.docker.com/r/toshsramen/tastyigniter/)
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/toshsramen/tastyigniter/latest)](https://hub.docker.com/r/toshsramen/tastyigniter/tags)
[![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/toshsramen/tastyigniter)](https://hub.docker.com/r/toshsramen/tastyigniter/builds)
[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/toshsramen/tastyigniter)](https://hub.docker.com/r/toshsramen/tastyigniter/builds)

Run with docker compose for automatic database configuration

    mkdir tastyigniter && cd tastyigniter
    curl -LO https://github.com/ToshsRamen/TastyIgniterDocker/raw/master/docker-compose.yml
    docker-compose up -d
    
Browse to port 8001 of your docker host. The TastyIgniter setup wizard will show up. Wait for a minute for the database container to come up and then run the setup. 


Alternatively if you don't want to use docker compose you can run it manually

    docker run -d -p 80:80 toshsramen/tastyigniter
    
Run the setup and connect to a mysql db.

## Credits
TastyIgniter: https://github.com/tastyigniter/TastyIgniter
