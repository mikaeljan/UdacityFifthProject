# Catalog Web Application - Udacity 5th Project
Flask driven Catalog App for Udacity's 5th project.
Some of the features:
- oAuth2.0 Google and FB login system
- SQLAlchemy handling of DB
- Flask framework
- Bootstrap

Files and directories:
1. Static - for .css and .js 
2. Templates - for .html files
3. JSON files - for Google and FB authentication
4. db_setup.py, db_populate.py - for creating and populating DB
5. itemscatalog.db - file representing the DB
6. application.py for running the file


# RUNNING
In order for everyone to simulate the same environment we use vagrant and virtual box.

## INSTALLATION 
  
  1. Download Vagrant and Virtual Box
  2. Download or clone Github Repo
  3. Python has to be installed on your computer. For details visit https://www.python.org/downloads/. 
    3.1. This project uses Python 2.7
  
## Executing the program
1. Navigate to the vagrant environment with this project already included

2. Run vagrant up and then vagrant ssh

3. Inside the project folder, run database.py to create the database using python database.py

4. (Optional, if you want to start from scratch, remove itemscatalog.db) Populate the database with categories by running db_populate.py 

5. Run application.py and navigate to localhost:8000 in your browser
