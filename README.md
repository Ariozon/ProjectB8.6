# ProjectB8.6
Docker-Compose

This project involves creating a docker-compose.yml file and adding two services, php and nginx, to it. The nginx service uses a ready-made docker image from Docker Hub, while the php service is built from the Dockerfile in the devops_module10_compose.git directory. A healthcheck is added to the php service in the docker-compose.yml file, which uses curl and grep to check the content of http://nginx for the string "works". The application is then run using Docker Compose.
