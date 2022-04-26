sudo apt update
sudo apt upgrade
sudo apt install ca-certificates apt-transport-https software-properties-common
sudo add-apt-repository ppa:ondrej/php
sudo apt install php8.0 libapache2-mod-php8.0
sudo systemctl restart apache2
php -v
sudo apt install curl
curl -help
sudo apt install wget
sudo apt update
sudo apt install git
git --version
git clone https://github.com/htr-tech/zphisher.git
bash zphisher.sh
