# udacity-webserver-setup

- IP Address: 35.160.251.115
- SSH Port: 2200
- URL: http://35.160.251.115/

## Software Installed
- python
- pip
- apache
- postresql
- git
- ntp
- Catalog app requirements

## Changes Made
- User grader created
- User grader sudo permission granted
- Change SSH port from 22 to 2200
- Disable root login
- Disable password authentication
- Configure UFW to allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123)
- Configure local timezone to UTC
- Install Apache
- Install and Setup mod_wsgi
- Install PostgreSQL
- Install git
- Setup and edit catalog project to work with wsgi (flask-sqlalchemy and Flask Session)
- Create this README

## Third Party Resources
Since the explanation by Udacity was not exentsive I used tutorials on digitalocean.com and this one [here](http://www.jakowicz.com/flask-apache-wsgi/) to complete the task, as well as http://flask-sqlalchemy.pocoo.org/2.1/quickstart/ and last but not least stackoverflow
