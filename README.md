#!/bin/bash
ec2-user
sudo -i
yum install httpd -y
cd /var/www/html
echo "welcome to devops engineer my name is shankar" >index.html
service httpd restart
this is my commit
