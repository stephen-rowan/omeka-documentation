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



