#Configure Ubuntu Server

Start your Ubuntu server virtual machine ...

##Check LAMP is working :

Go to [your-hostname]:8080 and you should see the Apache2 Ubuntu Default Page.

>If this is not working check that your port-forwarding settings are correct in Settings->Network->Advanced->Port-forwarding

##Update and upgrade Ubuntu Server :

* login to Ubuntu server

* switch to root:
>sudo su root

* update our system:
>apt-get update

* upgrade our system:
> apt-get upgrade

##Enable Apache mod_rewrite :

* Enable the Apache module mod_rewrite to allows Omeka to let you use custom URL paths:
>a2enmod rewrite

* Restart Apache:
> && service apache2 restart

##Set up the database :

* Log into the MySQL database program as the root user:
>mysql -u root -p

* Enter a command to create the database:
>CREATE DATABASE [database-name] CHARACTER SET utf8 COLLATE utf8_general_ci;


>CHARACTER SET utf8 COLLATE utf8_general_ci ensures that you can use the full character set in your web site, and not just the Latin character set.








