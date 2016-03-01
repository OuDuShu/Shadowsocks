# Shadowsocks

https://teddysun.com/342.html

vi /etc/resolv.conf   修改DNS配置
把114.114.114.114注释掉
/etc/init.d/shadowsocks restart

libev 版本shadowsocks

使用方法：
使用root用户登录，运行以下命令：

wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-libev.sh
chmod +x shadowsocks-libev.sh
./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log

Go版本shadowsocks

使用方法：
使用root用户登录，运行以下命令：
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-go.sh
chmod +x shadowsocks-go.sh
./shadowsocks-go.sh 2>&1 | tee shadowsocks-go.log

CentOS 6、7下pptp vpn一键安装脚本，安装如下：

- wget http://mirrors.linuxeye.com/scripts/vpn_centos.sh
- chmod +x ./vpn_centos.sh
- ./vpn_centos.sh

Python版本shadowsocks

使用root用户登录，运行以下命令：
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh
chmod +x shadowsocks.sh

./shadowsocks.sh 2>&1 | tee shadowsocks.log
