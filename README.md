Simple django deployer
======================

A simple deployer for a minimum django project sandbox includes: 

* Creation of user for the webapplication
* Checking out of the code from git
* Creating database on local VM (I said this is small instance right?)  
* Collectstatic and & migrate
* Setup UWSGI ran from systemd 
* Setup of nginx. 

Not really done, left a lot of boilerplate code from Galaxy, and some missing 
features. 