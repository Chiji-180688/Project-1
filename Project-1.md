## Project 1 Documentation
`sudo apt update`
`sudo apt install apache2`
`sudo systemctl status apache2`
![status apache2 image](./images/Apache%20status.PNG)
`curl http://localhost:80`
[testing apache http response to request from server](https://172.31.85.139:80)
	![IP Address in browser output](./images/IP%20Address%20in%20browser%20output.PNG)
`sudo apt install msql-server`
`sudo mysql`
`sudo mysql_secure_installation`
![mysql installation image](./images/Mysql%20secure%20installation.PNG)
`sudo mysql -p`
![mysql -p output](./images/Mysql%20-p%20output.PNG)
`sudo apt install php libapache2-mod-php php-mysql`
`php -v`
![php -v output](./images/php%20-v%20output.PNG)
`sudo mkdir /var/www/projectlamp`
` sudo chown -R $USER:$USER /var/www/projectlamp`
`sudo vi /etc/apache2/sites-available/projectlamp.conf`
![new configuration file in apache](./images/New%20configuration%20file%20in%20Apache2%20directory.PNG)
![list of files in the apache directory](./images/List%20of%20files%20in%20the%20apache%20directory.PNG)
`sudo a2ensite projectlamp`
`sudo a2dissite 000-default`
`sudo apache2ctl configtest`
![syntax status](./images/php%20syntax%20status.PNG)
[accessing my website using IP address](https://172.31.85.139:80)
![browser output](./images/IP%20Address%20in%20browser%20output.PNG)
`sudo vim /etc/apache2/mods-enabled/dir.conf`
![changing index.html to index.php](./images/Changing%20the%20order%20of%20listing%20of%20php.index%20files.PNG)
`sudo systemctl reload apache2`
`vim /var/www/projectlamp/index.php`
![php code](./images/php%20code.PNG)



