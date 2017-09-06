# Docker-cagette
Image Docker of the software Cagette (http://www.cagette.net) the free software of the short circuit

### Software Overview
Volunteers and coordinators, forget Excel sheets to send by mail, membership lists never up to date! Cagette.net simplifies the lives of coordinators and members by providing customized tools specifically designed for AMAPs and purchasing groups.
Tested on the ground since 2013, this software proposes concrete and useful tools: to manage the memberships and the orders, to plan the deliveries, to administer the list of products and producers ...
Do not waste time with bad tools, and concentrate on what is really important: Animate your group and develop short circuits!

### Installation
* Download zip file
* Unzip the zip file
* Go to the unzipped directory
* type the command "docker-compose up"
* Wait for the 2 docker containers to be created (MariaDB database and Cagette app)
* Open your favorite browser and enter: http://IPMachineOfDocker
* A page should be displayed the first time with the creation of crate tables, after a refresh of the page you are on the home page.
* Create the default admin user by going to http://IPMachineOfDocker/install
* There you go !

### ToDo
* Improve documentation on this Docker version
* Exporting volumes for a Cagette backup
* Using Swarm and Setting Service Mode (Cluster Mode)
* Using a Letsencrypt certificate (with 2 additional reverse-proxy and letsencrypt companion containers)
* Your contributions ......

### How to contribute?
* By going to the crate forum: https://groups.google.com/forum/#!forum/cagette and participating in the exchanges (all alone we go faster but together we go further)
* By participating in this depot to improve / optimize this version of Cagette in Docker

### Thanks
We thank tyjak because we are based on its creation of a Docker version of Cagette (https://github.com/tyjak/docker_cagette)
We thank the cage team and its installation documentation which allowed us to build this version Docker
Thank you for using this Docker version and your feedback
