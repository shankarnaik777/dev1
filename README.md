#!/bin/bash
ec2-user
sudo -i
yum install httpd -y
cd /var/www/html
echo "welcome to devops engineer" >index.html
service httpd restart
