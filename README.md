# wireguard-ipv6
本脚本在https://github.com/hongwenjun/vps_setup 的，一键安装wireguard脚本基础上增加了ipv6功能，再次特别感谢hongwenjun大佬。
该脚本仅在Vultr及digitalocean的VPS上测试通过。客户端配置文件在VPS的/etc/wireguard文件夹内，本脚本共生成9个客户端配置文件。

debian系统一键安装wireguard带IPv6脚本

wget -qO- git.io/fhhea | bash

ubuntu系统一键安装wireguard带IPV6脚本

wget -qO- git.io/fhjAT | bash

centOS系统一键安装wireguard带IPV6脚本(在Vultr上测试通过）

目前centOS7需要升级系统内核，因此首先使用命令升级系统内核，在使用一键安装脚本，如果系统安装wget,使用yum install wget进行安装。

Centos 升级内核命令

wget -qO wg.sh git.io/fhnhS && bash wg.sh kernel

wireguard带IPv6一键脚本

wget -qO- git.io/fhjAm | bash
