yum install -y docker
# Make SwapFile
sudo dd if=/dev/zero of=/var/swap bs=1M count=1024
mkswap /var/swap
swapon /var/swap