### Rename existing html directory and replace it with new one
mv /var/www/html /var/www/html_old
cp -r ecommerce/html  /var/www/

### Stop/Start/status/enable httpd service
sudo systemctl stop httpd
sudo systemctl start httpd
sudo systemctl status httpd
sudo systemctl enable httpd
