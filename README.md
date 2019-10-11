 docker pull nginx
 docker run --name mynginx1 -p 80:80 -d nginx
 
 docker ps
 
 create docker file :
 From alpine:3.4
 add apk curl
 add apk vim
 
 save and push to docker hub
 docker pull jitinkumar2019/alpinejitin
 
 docker images
 docker run --rm -ti jitinkumar2019/alpinejitin /bin/sh
  cat /etc/os-release
  curl --version
  vim --version
