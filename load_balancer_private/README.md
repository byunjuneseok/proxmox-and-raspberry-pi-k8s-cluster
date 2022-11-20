# Install haproxy @Ubuntu
sudo apt install --no-install-recommends software-properties-common
sudo add-apt-repository ppa:vbernat/haproxy-2.6 -y
sudo apt-get install haproxy=2.6.\*
sudo apt-get update
sudo apt-get upgrade -y

LTS version : http://www.haproxy.org/


# Install keepalived @Ubuntu
sudo apt-get install keepalived
vim /etc/keepalived/keepalived.conf
sudo systemctl restart keepalived


# Reference
- https://www.haproxy.com/blog/how-to-install-haproxy-on-ubuntu/

