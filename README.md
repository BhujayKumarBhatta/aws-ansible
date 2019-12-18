# aws-ansible
https://bhujaykbhatta.wordpress.com/2019/05/09/convert-infrastructure-as-code-with-ansible-aws/


gitlab for iac

ping gitlab.example.com
PING gitlab.example.com (192.168.111.131) 56(84) bytes of data.
64 bytes from dbserver (192.168.111.131): icmp_seq=1 ttl=64 time=0.934 ms


 ssh root@gitlab.example.com


docker pull gitlab/gitlab-runner
docker logs gitlab-runner
docker ps
docker pull gitlab/gitlab-ce
sudo docker run --detach   --hostname gitlab.example.com   --publish 443:443 --publish 80:80 --publish 22:22   --name gitlab   --restart always   --volume /srv/gitlab/config:/etc/gitlab:Z   --volume /srv/gitlab/logs:/var/log/gitlab:Z   --volume /srv/gitlab/data:/var/opt/gitlab:Z   gitlab/gitlab-ce:latest
netstat -lntp
service apache2 stop
sudo docker run --detach   --hostname gitlab.example.com   --publish 443:443 --publish 80:80 --publish 22:22   --name gitlab   --restart always   --volume /srv/gitlab/config:/etc/gitlab:Z   --volume /srv/gitlab/logs:/var/log/gitlab:Z   --volume /srv/gitlab/data:/var/opt/gitlab:Z   gitlab/gitlab-ce:latest
docker ps
docker rm gitlab
sudo docker run --detach   --hostname gitlab.example.com   --publish 443:443 --publish 80:80 --publish 22:22   --name gitlab   --restart always   --volume /srv/gitlab/config:/etc/gitlab:Z   --volume /srv/gitlab/logs:/var/log/gitlab:Z   --volume /srv/gitlab/data:/var/opt/gitlab:Z   gitlab/gitlab-ce:latest
docker rm gitlab
sudo docker run --detach   --hostname gitlab.example.com   --publish 8929:80 --publish 2289:22   --name gitlab   --restart always   --volume /srv/gitlab/config:/etc/gitlab   --volume /srv/gitlab/logs:/var/log/gitlab   --volume /srv/gitlab/data:/var/opt/gitlab   gitlab/gitlab-ce:latest
docker ps
sudo docker exec -it gitlab /bin/bash
docker stop gitlab
docker start gitlab
docker ps
telnet
netstat -lntp
curl
curl localhost:8929
curl -k localhost:8929
curl -k https://localhost:8929
docker ps
curl -k https://localhost
sudo docker logs gitlab
sudo docker exec -it gitlab /bin/bash
netstat -lntp
telnet localhost 8929
docker ps
docker rm gitlab
docker stop gitlab
docker rm gitlab
sudo docker run --detach   --hostname gitlab.example.com   --publish 80:80 --publish 2289:22   --name gitlab   --restart always   --volume /srv/gitlab/config:/etc/gitlab   --volume /srv/gitlab/logs:/var/log/gitlab   --volume /srv/gitlab/data:/var/opt/gitlab   gitlab/gitlab-ce:latest
curl localhost
docker ps
curl localhost
telnet localhost 80

sudo docker logs gitlab
curl localhost
docker ps
telnet localhost 80
curl localhost
sudo docker exec -it gitlab editor /etc/gitlab/gitlab.rb
sudo docker restart gitlab
docker ps
while true; do docker ps; sleep 2;done
curl localhost
hostname -I
docker pull python:alpine3.8
docker exec gitlab bash
docker exec -it gitl bash
sudo docker exec -it gitlab editor /etc/gitlab/gitlab.rb
sudo docker exec -it gitlab /bin/bash
sudo docker restart gitlab
while true;do docker ps; sleep 3 ; done
sudo docker restart gitlab-runner
while true;do docker ps; sleep 3 ; done
docker exec -it gitlab-runner bash
sudo docker exec -it gitlab /bin/bash
docker exec -it gitlab-runner bash
sudo docker restart gitlab-runner

sudo docker exec -it gitlab /bin/bash
docker exec -it gitlab-runner bash
sudo docker exec -it gitlab /bin/bash
sudo docker restart gitlab-runner
docker exec -it gitlab-runner bash
sudo docker restart gitlab-runner
docker exec -it gitlab-runner bash
docker ps
docker exec -it gitlab-runner bash
docker stop gitlab-runner
docker rm gitlab-runner
docker ps
vi   /srv/gitlab-runner/config/config.toml
docker stop gitlab-runner
docker ps
docker stop
docker stop gitlab-runner
docker ps
docker rm gitlab-runner
docker ps

vi   /srv/gitlab-runner/config/config.toml
docker stop gitlab-runner
docker rm gitlab-runner
docker ps
docker exec -it gitlab-runner bash
docker stop gitlab-runner
docker rm gitlab-runner
docker stop gitlab-runner
docker rm gitlab-runner
vi   /srv/gitlab-runner/config/config.toml
docker exec -it gitlab-runner bash
vi   /srv/gitlab-runner/config/config.toml
docker exec -it gitlab-runner bash
docker run --rm -t -i -v /srv/gitlab-runner/config:/etc/gitlab-runner gitlab/gitlab-runner register
vi   /srv/gitlab-runner/config/config.toml
docker exec -it gitlab-runner bash
shutdown -t now
pwd
ls -l
netstat -lntp
docker --?
pwd
docker cp aws_auth.yml
docker cp aws_auth.yml gitlab-runner:/home/gitlab-runner/builds/sJu85zW6/0/user1/aws-ansible/
docker cp aws_auth.yml gitlab-runner:/home/gitlab-runner/
docker ps
sudo docker run --detach   --hostname gitlab.example.com   --publish 80:80 --publish 2289:22   --name gitlab   --restart always   --volume /srv/gitlab/config:/etc/gitlab   --volume /srv/gitlab/logs:/var/log/gitlab   --volume /srv/gitlab/data:/var/opt/gitlab   gitlab/gitlab-ce:latest
docker start gitlab
netstat -lntp
service apache2 stop
docker start gitlab
while true;do docker ps; sleep 3 ; done
docker run --rm -t -i -v /srv/gitlab-runner/config:/etc/gitlab-runner gitlab/gitlab-runner register
docker exec -it gitlab-runner bash
ls -l
docker cp id_rsa.pub.bhujay gitlab-runner:/home/bhujay/id_rsa.pub
docker run --rm -t -i -v /srv/gitlab-runner/config:/etc/gitlab-runner gitlab/gitlab-runner register
shutdown -t now
docker ps
docker start gitlab
service stop apache2
service apache2 stop
docker start gitlab
hostname -I


while true;do docker ps; sleep 3 ; done
hostmame -I
hostname -I
compgen |grep ubuntu
vi /etc/ssh/sshd
vi /etc/ssh/sshd_config
su -
ls -l
shutdown -t now



 
