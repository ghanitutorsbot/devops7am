Docker cli commands - Commands

docker info
docker version
docker images
docker ps
docker rmi imagename
docker login


docker pull imagename
docker run imagename
 options: -d , -it(exit  Ctrl+p+q)
docker attach containerid/name
docker exec -it containerid/name /bin/bash

docker commit containerid/name dockerusername/newimagename 
docker push dockerusername/newimagename