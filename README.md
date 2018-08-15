---
layout: "post"
title: "README"
date: "2018-08-12 13:56"
---
# Item Catalog Project
Developed a content management system using the Flask framework in Python. Authentication is provided via OAuth and all data is stored within a PostgreSQL database. Authenticated users will have the ability to post, edit, and delete their own items.  
This project shows different categories of novels.

## Tools and Frameworks
This web application was built with HTML5, CSS, Bootstrap, Vagrant, Flask, SQLAlchemy & Google Oauth2 APIs.

## Instruction
To run the web application:  
1. Install Vagrant and Virtual Box  
2. Launch the Vagrant VM (by typing `vagrant up` in the directory */udacity-catalog-project* from the terminal).  
4. From directory */udacity-catalog-project/catalog*, initialize the application database by typing `python database_setup.py` follows by `python feedcatalog.py`.  
5. From directory */udacity-catalog-project/catalog*, run the application within the VM by typing `python main.py` into the Terminal.  
6. Access the application by visiting http://localhost:8080 locally on the browser.

## License
MIT License

Copyright (c) [2018] [item-catalog]
