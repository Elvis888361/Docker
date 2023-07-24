# Docker
insidethe Dockerfile you need to input this
FROM node:alpine-it installs the node on any other OS
COPY ./app it knows the app thats being run
WORKDIR /app it knows the directory the file thats being run on
CMD node app.js - it run the file  with this steps you will be an=bele to run the file


how to run the Docker

docker image ls
to see the images that there are
docker run imagename
this is the name of the file  thats being runned

How to pull an image into any os in order to run it 
docker pull imagename
from there follow the above procedure
