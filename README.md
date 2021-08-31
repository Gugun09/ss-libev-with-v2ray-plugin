# ss-libev-with-v2ray-plugin

# Usage Installation
## CentOS 7/8
wget -O centos-ss-install.sh https://raw.githubusercontent.com/Gugun09/ss-libev-with-v2ray-plugin/main/centos-ss-install.sh
chmod +x centos-ss-install.sh
./centos-ss-install.sh

## Ubuntu 18.04/16.04 or Debian 9/10
wget -O ss-install.sh https://raw.githubusercontent.com/Gugun09/ss-libev-with-v2ray-plugin/main/debian-ss-v2ray-install.sh
chmod +x ss-install.sh
./ss-install.sh

# Manage shadowsocks with systemctl
systemctl status shadowsocks

systemctl start shadowsocks

systemctl stop shadowsocks
