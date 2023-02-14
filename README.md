ssh -i "C:\Users\miche\Downloads\private-key.pem" Ubuntu@ec2-34-242-14-221.eu-west-1.compute.amazonaws.com
sudo apt-get install apache2
sudo apt-get install mysql-server
sudo apt-get install php-mysql
sudo apt-get install php
sudo apt-get install libapache2-mod-php
sudo apt-get install php-mcrypt
sudo apt-get install php-pear
sudo apt-get install curl
sudo apt-get install php-curl
sudo apt-get install php-cli
sudo apt-get install git
a2enmod rewrite
sudo systemctl restart apache2
cd var/www/html
pwd
sudo git clone https://github.com/mikematar1/stunning-laravel.git
curl -sS https://getcomposer.org/installer | sudo php — — installdir=/
usr/local/bin — filename=composer
curl -sS https://getcomposer.org/installer | sudo php -- -- installdir=/
usr/local/bin — filename=composer
sudo composer install
cp .env.example .env
vim .env
php artisan key:generate
which apache2
ls -al
vim apache2.conf
cd sites-enabled
vim ooo-default.conf
sudo systemctl restart apache2
cd var/www/html/stunning-laravel
sudo chgrp -R www-data storage bootstrap/cache
sudo chmod -R ug+rwx storage bootstrap/cache”.
