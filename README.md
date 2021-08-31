# ss-libev-with-v2ray-plugin

# Usage Installation
## CentOS 7/8
wget -O centos-ss-install.sh https://github.com/M3chD09/shadowsocks-with-v2ray-plugin-install/raw/master/centos-ss-install.sh
chmod +x centos-ss-install.sh
./centos-ss-install.sh

## Ubuntu 18.04/16.04 or Debian 9/10
wget -O ubuntu-ss-install.sh https://github.com/M3chD09/shadowsocks-with-v2ray-plugin-install/raw/master/ubuntu-ss-install.sh
chmod +x ubuntu-ss-install.sh
./ubuntu-ss-install.sh

# Manage shadowsocks with systemctl
systemctl status shadowsocks

systemctl start shadowsocks

systemctl stop shadowsocks
