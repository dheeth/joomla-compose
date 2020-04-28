# joomla-compose
Here is the Final docker-compose file for running 1-click Installation and Joomla CMS up in few seconds

This Infrastructure uses mysql:5.7 image for the database
joomla:php7.3-apache for the joomla cms

It creates 2 volumes joomla_storage and mysql_storage where your persistent data will be stored so that you do not lose anything and you can launch any number of containers as required without losing any data. These volumes work as centeralized storage for all the containers
