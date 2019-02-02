# Linux_Server_Configuration
Linux Server Configuration

## Project Description
Take a baseline installation of a Linux distribution on a virtual machine and prepare it to host your web applications, to include installing updates, securing it from a number of attack vectors and installing/configuring web and database servers. 

- IP address: 35.159.0.214

- Accessible SSH port: 2200 

- Application URL: http://ec2-35-159-0-214.eu-central-1.compute.amazonaws.com/

## Walkthrough

- create lightsail instance 
- run '$ sudo apt-get update $ sudo apt-get upgrade' and '$ sudo apt-get dist-upgrade' 
- Changing the SSH port from 22 to 2200 
- Configure the Uncomplicated Firewall (UFW) 
- Check the status of UFW to list current roles: sudo ufw status. 
- create user grader 
- Giving grader access 
- Creating an SSH key-gen and public key 
- Configure the local timezone to UTC 
- Install and configure Apache to serve and Python mod_wsgi application 'sudo apt-get install apache2' 
- Install and configure PostgreSQL 'sudo apt-get install postgresql'
- Create a new PostgreSQL for catalog 
- Install git 'sudo apt-get install git' 
- Clone and setup the Item Catalog project from the GitHub repository 
- Authenticate login through Google 
- Reinstall the corresponding JSON file, open it and copy the contents. 
- Configure and Enable our virtual host to run the site 'sudo nano /etc/apache2/sites-available/catalog.conf'

## reference
https://github.com/Heba-ahmad/FSND-P5-walkthrough/blob/master/Linux-Server-Configuration-p5-walkthrough.pdf
https://github.com/mulligan121/Udacity-Linux-Configuration



