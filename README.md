# Simple Web Application

This is a simple web application using [Python Flask](http://flask.pocoo.org/) and [MySQL](https://www.mysql.com/) database. 
This is used in the demonstration of development of Ansible Playbooks.
  
  Below are the steps required to get this working on a base linux system.
  
  - Install all required dependencies
  - Install and Configure Web Server
  - Start Web Server
   
<<<<<<< HEAD
## 1. Install all required dependencies
  
  Python and its dependencies

    apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb

=======
## 1. Install python
  
  Python and its dependencies

    apt update && apt full-upgrade -y  && apt install python-pip -y 
>>>>>>> 80867beb928a67d56f66ca6bc74a14fa605a095f
   
## 2. Install and Configure Web Server

Install Python Flask dependency

<<<<<<< HEAD
    pip install flask
    pip install flask-mysql

- Copy app.py or download it from source repository
- Configure database credentials and parameters 
=======
    pip2 install flask

- Copy app.py or download it from source repository 
>>>>>>> 80867beb928a67d56f66ca6bc74a14fa605a095f

## 3. Start Web Server

Start web server

    FLASK_APP=app.py flask run --host=0.0.0.0
    
## 4. Test

Open a browser and go to URL

<<<<<<< HEAD
    http://<IP>:5000                            => Welcome
    http://<IP>:5000/how%20are%20you            => I am good, how about you?
=======
    http://<IP>:8080                           
>>>>>>> 80867beb928a67d56f66ca6bc74a14fa605a095f
