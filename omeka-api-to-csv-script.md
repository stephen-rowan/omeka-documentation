#Omeka API to CSV Script

* This python script can be found at https://github.com/omeka/PythonOmekaApiToCsv.

* It was run successfully on Python 2.7.12 after installing python-pip (The PyPA recommended tool for installing Python packages) and then httplib2 ...
>sudo apt install python-pip
>pip2 install httplib2 --upgrade

* The script prompts for your Omeka API endpoint[^1]. The Omeka endpoint is the URL to your Omeka website followed by /api, like this:
>http://yourdomain.com/api


* This script produced the following csv files :

>element_sets_output.csv

>elements_output.csv

>files_output.csv

>items_output.csv

>tags_output.csv



[^1]: See [APIs for beginners](http://omeka.readthedocs.io/en/latest/Reference/api/for_beginners.html#omeka-s-rest-api) on the Omeka website.




