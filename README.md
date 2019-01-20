## This is a project for udacity FSND 

### ip 35.158.243.213
### port 2200 for ssh
### complete URL 35.158.243.213.xip.io


## Summary of software installed and configuration changes made 

1) created a new user "grader"
2) added sudo access to "grader"
3) created a publicKey for ssh
4) changed /etc/ssh/ssh_config port from 22 to 2200
5) added the following ports to ufw 123 , 2200 , 80
5) enabled ufw
6) changed time to UTC
7) installed apache, Flask and mod_wsgi
8) installed git
9) cloned my project ItemCatalog to /var/www/ItemCatalog
10) deleted /var/www/html
11) deleted /ect/apache2/sites-available/000-default.conf
12) created a new conf file ItemCatalog.conf
13) changed /var/www/ItemCatalog/ItemCatalog/__init_ _.py  sqlite to new directory and client_secret.json to new directory

## list of third-party
1) slack/UconnectSaudi
2) http://flask.pocoo.org/
3) https://stackoverflow.com/
4) https://knowledge.udacity.com/
