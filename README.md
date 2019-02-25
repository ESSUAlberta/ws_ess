# ESS Web service

Simple webservice for the ESS website backend
This ReadMe is a WIP

## Description

This is a Flask webservice that will run on the ESS server to handle some of the services that the ESS website requires. 

This webservice will do things such as:
* Authenticate ESS volunteers so they can edit the site
* Store links to images 


## Getting Started
To clone this to develop on
'''
git clone http://linkt-to-this-repo.git
virtualenv env
source env/bin/activate
pip3 install -r requirements
'''
### Dependencies

* Designed for and tested on Ubuntu 
* virtualenv
* Python3
* Flask
* Authlib
* MongoDB

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

Below is how to run this application on the ESS server
```
$ git pull http://link-to-this-repo.git
$ export FLASK_APP=hello.py
$ flask run
 * Running on http://127.0.0.1:5000/
```

## Help
Contact director.it@ess.ualberta.ca for help