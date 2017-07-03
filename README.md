Pet-Detective

The app that helps the hunt for lost pets!
#Team
Copypasta

Product Owner: Tourne Torres
Scrum Master: Daniel Weill
Development Team Members: Tourne Torres, Taijon Robinson, Daniel Weill
Table of Contents

#Usage
##Requirements
##Development
##Installing Dependencies
##Tasks
##Team
##Contributing
#Usage

##Some usage instructions
##Requirements
Node 6.10.2
MySQL 5.7.18
express
body-parser
dotenv

Place these keys in a config file inside of your *client* folder
window.GEOCODE_API_KEY = 'YOUR GEOCODE API KEY';

window.PLACES_API_KEY = 'YOUR PLACES API KEY';

Create a .env file to store port and database variables. Localhost will suffice for db in most cases/

You will need a database called petdetective, created in a mysql session. Once used, create a table called petpost with the following command: create table petpost (id integer not null auto_increment, lostOrFound varchar(20), type varchar(20) , address varchar(140), message varchar(140), date varchar(140), latlong varchar(140), primary key (id));
##Development

##Installing Dependencies

###From within the root directory:
Run this command:
npm install

It's that simple!
##Contributing

See CONTRIBUTING.md for contribution guidelines.

![img](https://upload.wikimedia.org/wikipedia/en/thumb/6/62/MySQL.svg/1200px-MySQL.svg.png)

![img](http://kartikgola.com/wp-content/uploads/2017/02/express3.png)


![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-BLdbYkpNZFei4Ok3tusGUT6hl3sy-QEHWuWPAIugq4cEoq3e)
