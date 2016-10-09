Simple django deployer
======================

A simple deployer for a minimum django project sandbox includes: 

* Creation of user for the webapplication
* Checking out of the code from git
* Creating database on local VM (I said this is small instance right?)  
* Collectstatic and & migrate
* Setup UWSGI ran from systemd 
* Setup of nginx. 

This works (I have deployed some small production systems using it)
