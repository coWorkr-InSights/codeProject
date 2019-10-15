coWorkr Test Project
============

![Sample Chart](<Website URL>)

## Project Summary

###Objective
Quick test website to show proficiency in Linux, Meteor, MongoDb, Javascript and general web/server coding.

###Goals
Put together a GCE instance with a simple actively updating graph of random data.  Time vs Random number.

###Outline
A quick GCE server instance running meteor and MongoDb.  

* Clone this repository for the project code.
* Create a free GCE instance running Ubuntu 18 with HTTP/HTTPS ports open
* Install the free version of MongoDB 4.2.
* Install Meteor and Node.
* Create a server script that randomly updates a Mongo collection with time series data.  (Date, Number).  You can use whatever you want but most of our server scripts are in NodeJS using the Mongo NPM driver.  So that would be a plus.
* Create a Meteor website page (no login required) that activity pulls and updates a graph with the last 20 or so elements from the collection.  Pick whatever open source graphing/charting package you would like to use.  
* The data should be supplied to the client using Meteor sub/pub system.
* Use GitHub and Git to upload the code to the cloned repository, so we can take a look.  Only document what is not obvious by reading the code.


###Extras:  
We use the following packages on the site.  If you have time and want to use them would be a plus.

* https://materializecss.com - Front end CSS framework

* https://c3js.org - One of the charting packages we use.

* https://www.chartjs.org - Another one.
