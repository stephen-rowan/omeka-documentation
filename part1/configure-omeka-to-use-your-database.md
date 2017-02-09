#Configure Omeka to Use Your Database

* Install nano editor :
>apt-get install nano

* Go to the root of your omeka directory :
>cd /var/www/html/omeka

* Edit the db.ini file :
>nano db.ini

* Change the owner of our Omeka installation, so that it’s readable by the Internet:
>chown -R www-data:www-data .

