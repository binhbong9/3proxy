
cd /tmp


sudo yum update -y 

sudo yum install -y epel-release

sudo yum install -y centos-release-scl-rh

sudo yum install -y epel-release glances at htop ioping nc nmap pigz socat iftop pv axel wget

sudo yum groupinstall -y 'Development Tools'

sudo yum update -y 

sudo yum install -y php

sudo yum update -y 




cd /tmp


pkill -9 3proxy

pkill -9 3proxy

rm -rf /data/3proxy

rm -rf /usr/local/etc/3proxy

rm -rf /home/dncloud

mkdir -p /data/3proxy

cd /data/3proxy


\# curl -sO https://raw.githubusercontent.com/binhbong9/3proxy/main/c7-ipv6-init.sh && chmod +x c7-ipv6-init.sh && bash c7-ipv6-init.sh


wget https://raw.githubusercontent.com/binhbong9/3proxy/main/setup.sh && chmod +x setup.sh && bash setup.sh

