a. Pull `nginx:alpine-perl` docker image on `Application Server 1`.  

`docker pull nginx:alpine-perl`

b. Create a container named `news` using the image you pulled.  

`docker run --name news -d -p 3000:80 nginx:alpine-perl`

c. Map host port `3000` to container port `80`. Please keep the container in running state.
