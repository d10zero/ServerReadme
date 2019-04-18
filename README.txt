README

IP ADDRESS:
- 18.212.209.237

SSH port: 2200

USER INSTRUCTIONS (complete URL):
- Navigate to 'http://www.18.212.209.237.xip.io'


Software Installed:
- Postgresql
- SQLAlchemy
- Apache 
- mod_wsgi
- python-pip
- Flask
- Sqlalchemy,
- Passlib,
- oauth2client
- flask_httpauth

INSTALLATION
- Create mod_wsgi file for the web application
- Enable site and mod_wsgi
- moved Google's client secret key outside of the main method.


CONFIGURATION CHANGES 
Firewall changes:
- Allowed SSH port 2200
- Allowed Custom port 123
- Modify Amazon firewall to match

THIRD PARTY:
- Used this link 'https://www.jakowicz.com/flask-apache-wsgi/' for a lot of the wsgi setup


REQUIREMENTS:
- You must have an internet connection


WHAT THIS PROJECT DOES
- This project allows anyone to view already existing Categories and Items
- within those categories. Anyone can log into the application through google.
- The application uses google oauth authentication. The user, once logged in,
- can then add new items to already existing categories, and edit/update and
- delete any item that they have created. The user cannot edit/update or
- delete any items that they did not create, 

