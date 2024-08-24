https://66c9a14bbd7394aeb9e20be2--stalwart-cendol-c187de.netlify.app/

VM Image: Ubuntu 20.04 LTS

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

git clone https://github.com/nikitastras/CS2550-Project1.git

Google Cloud IP: http://35.226.28.138/
