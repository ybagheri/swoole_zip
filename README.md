# swoole_zip
create swoole.so using officail site

https://www.swoole.co.uk/docs/get-started/installation

make for Linux Centos centos-release-7-2.1511.el7.centos.2.10.x86_64

## for adding to your php module
sudo cp /your/swoole.so/path /usr/lib64/php/modules

## add the extension=swoole.so to the end of php.ini
sudo echo "extension=swoole.so" >>  /etc/php.ini  
## check if the swoole extension has been enabled
php -m | grep swoole                       
