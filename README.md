# finalProjectND
## About
This project is for Udacity FullStack ND
## Details Regarding the project
* For SSH
  IP - 54.80.235.248 Port - 2200
* URL - https://m.iap.infosysapps.com/
## Summary of Software Installed
* Apache2 Web Server
* PostgreSQL
* Python2, Flask and SQLAlchemy
## Configuration changes made on the server
* Configured ufw for 80, 123, 2200.
* Configured the local timezone to UTC.
* Configured the psql to disallow remote connections.
* Stopped Root ssh login.
* Changed the apache2 000-default.conf in /etc/apache2/sites-available directory to point to the Item catalog application wsgi file.
* Updgraded all the installed packages to the latest version.
* Created a grader user and gave sudo access.
## Third Party resources and other configurations
* Used nginx to route the request for https domain name.
* Used Google Oauth2 to implement login fuctionality in the project
