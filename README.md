如果“回车”后没有出现下图的菜单：
CentOS 系统请输入
yum install -y curl
Ubuntu / Debian系统请输入
sudo apt install -y curl
然后再次运行上面的命令：

bash <(curl -sL https://raw.githubusercontent.com/becapital/xray/main/xray.sh)   
更新日：2022-03-17

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
