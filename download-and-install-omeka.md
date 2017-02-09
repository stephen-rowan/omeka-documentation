#Download and Install Omeka

* Install unzip :
>apt-get install unzip

* Go to root of the html folder on your Ubuntu server :
>cd /var/www/html

* Logged in as the root user with *su root* download Omeka: 
>wget http://omeka.org/files/omeka-2.4.1.zip [^4]

* Unzip omeka-2.4.1.zip :
>unzip omeka-2.4.1.zip

* Remove omeka-2.4.1.zip :
>rm omeka-2.4.1.zip

* If you want your Omeka web site to have the URL http://your-domain.com/omeka/, change the name of the directory:
>mv omeka-2.4 omeka

[^4]: Omeka Version History is available at http://omeka.org/codex/Version_History
