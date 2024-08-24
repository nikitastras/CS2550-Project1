https://66c98724b3f6bc94812f6e70--enchanting-tarsier-22c989.netlify.app/

Instructions:
Setting up Nginx to host through Google Cloud on a Linux VM
$ sudo apt update
$ sudo apt install nginx -y
$ sudo systemctl start nginx
$ sudo systemctl enable nginx
#### Allows Nginx access through firewall
$ sudo ufw allow 'Nginx HTTP'
#### Check server status Green means go
$ sudo systemctl status nginx
#### Default path
cd /var/www/html
