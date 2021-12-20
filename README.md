# docker-cron
An example of running cron job in a docker container

# hapus container
docker rm <container_name>

# hapus image
docker image rm docker-cron:latest


# build image
docker build -t docker-cron .
docker run -dp 3000:3000 docker-cron:latest

