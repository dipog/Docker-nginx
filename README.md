#my steps

1. hostname
2. ip a
(inet 127.0.0.1/8)
3. sudo yum install httpd

**if an error is received like : cannot find a valid baseurl for repo base7x86 64. then run the below:
sudo dhclient (install packages)

4. sudo yum install httpd
5. systemctl start httpd
6. systemctl enable httpd
7. firewall-cmd --list-all
8. firewall-cmd --permamnent --zone=public --add-service=http
9. firewall-cmd --permamnent --zone=public --add-service=https
10. firewall-cmd --reload
11.firewall-cmd --list-all
12. cd /var/www/html/
13. ls
14. 

