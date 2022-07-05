安装命令：
bash <(curl -sL https://raw.githubusercontent.com/becapital/xray/main/xray.sh)  

如果“回车”后没有出现下图的菜单：
CentOS 系统请输入: yum install -y curl
Ubuntu / Debian系统请输入: sudo apt install -y curl

更新日：2022-07-05

Xray 一键脚本可以配置常规 VMESS 协议、VMESS+KCP、VMESS+websocket+TLS+Nginx、VLESS+TCP+XTLS、VLESS+TCP+TLS、trojan、trojan+XTLS 等多种组合，支持 CentOS 7/8、Ubuntu 16.04、Debian 8 及最新版系统

-------------------------------------------
升级Ubuntu14.06=  

apt-get update 

apt-get upgrade

apt-get dist-upgrade

do-release-upgrade

重启：

lsb_release -a
--------------------------------------------
一键原文： https://v2xtls.org/xray%E4%B8%80%E9%94%AE%E8%84%9A%E6%9C%AC/
