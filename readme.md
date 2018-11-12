# install docker
yum install -y docker

# setting user group
laravel...


# Make SwapFile
sudo dd if=/dev/zero of=/var/swap bs=1M count=1024
mkswap /var/swap
swapon /var/swap

sudo setenforce 0

# docker network create
docker network create -d bridge shared-nginx