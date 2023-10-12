
cd /tmp

pkill -9 3proxy

pkill -9 3proxy

rm -rf /data/3proxy

rm -rf /usr/local/etc/3proxy

rm -rf /home/dncloud

mkdir -p /data/3proxy

cd /data/3proxy

wget https://raw.githubusercontent.com/binhbong9/3proxy/main/setup.sh && chmod +x setup.sh && bash setup.sh

