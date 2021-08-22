# WildLife Tracker Java App :

### By Sultan Mwangovya Kirigha

## Description :notebook:

The Forest Service is considering a proposal from a timber company to clearcut a nearby forest of Douglas Fir.
Before this proposal may be approved, they must complete an environmental impact study.
This application allows Rangers to track wildlife sightings in the area, record them and ensure the animals are isolated to a safer zone.
All with the help of a user-friendly interface and fast database.

 

### Prerequisites

 * An up-to-date browser, preferably chrome or mozilla
 * Internet connection !


### Technologies used

   * JAVA
   * Gradle
   * Spark
   * Postgres SQL
   * HTML
   * CSS & Bootstrap
   * Junit

### Installation guide 

  If you want to use this as your template, here's how to go about it:

  * Install Git on you machine
  * Go to 'clone or download' button and get the link
  * --Linux Users-- open your terminal and run the 'git clone ...' command in a directory of your choice
  * --for Windows Users-- Navigate to the location you'd want the repository located, right click and select "git bash here"
  * Clone the repository
  * Upon completion, navigate to the cloned repository
  Feel free to edit the files to your prefered taste

  * Now build the Database to enable storing of created instances
  * Install Postgres SQL
  * run the following commands in your terminal

        CREATE TABLE users (id serial primary key, name varchar, position varchar, role varchar, department varchar);
        CREATE TABLE news (id serial primary key, title varchar, description varchar, type varchar, author varchar);
        CREATE TABLE departments (id serial primary key, name varchar, description varchar, totalemployees int);
        CREATE TABLE departments_users (id serial primary key, deptid int, userid int);
        CREATE TABLE departments_news (id serial primary key, deptid int, newsid int, userid int);
        CREATE DATABASE news_portal_test WITH TEMPLATE news_portal;



### BUGS
NO BUGS noted, If any are experienced contact via Email sultankirigha@gmail.com :mailbox: and the issue will be sorted.


### LICENSE
 This website is under the MIT license which can be found [HERE](LICENSE).
 Copyright (c) 2021 Sultan Mwangovya Kirigha