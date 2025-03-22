# --- ***                                         *** --- #
# NextCloud Server with Docker, for test labs             #
# from OS Mint 21 .                                       #
# --- ***                                         *** --- #

--- youtube ---
https://youtu.be/0TqGVbH0FRc

--- github repository ---
https://github.com/ggvhcs/cloud

Develop Enviroment:
---
Linux Mint 21.2 Mate x64.
Docker version 24.0.7, build 24.0.7-0mint2~21.1
git version 2.34.1
Github Desktop version 3.2.0-linux1 (x64)
Visual Studio Code version 1.96.4
---

1 --- download image nextcloud from hub docker ---
$ sudo docker pull nextcloud:latest // command for downnload image.
$ sudo docker images |grep nextcloud // una vez descargada, check it.
$ sudo docker pull mariadb:10.6 // command for downnload image.
$ sudo docker images |grep mariadb // una vez descargada, check it.

2 --- setting docker-compose file ---
$ sudo nano ~/Documents/GitHub/docker/cloud/docker-compose.yml

3 --- set up an test container ---
$ cd ~/Documents/GitHub/docker/cloud
$ sudo docker-compose up -d
$ sudo docker-compose ps

5 --- dansboard interface, if you want we can enter for portainer dansboard. ---
http://localhost:8080
user --> admin
pass --> blabla25*

--- bibliography ---
https://hub.docker.com/_/nextcloud
