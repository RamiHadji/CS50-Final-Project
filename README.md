# My Notes Web Application

## This is my final project for Harvard's CS50x : Introduction to Computer Science course.

#### Video Demo:   https://www.youtube.com/
#### Description:
 "My Notes"

## Hello, my name is: 
 #### Hadji Rami I am from Algeria and I live in M'sila

## This is my final project for Harvard's CS50.
 
Here I will give some details about the project. 
## Introduction
  This *My Notes*  It is an easy to use website You can take notes. You can write down
  
  what is on your mind quickly and refer to it at any 
 time 
and from anywhere. 
On this site, you can easily write notes, memos, emails, letters and shopping lists.

And many, many ideas.
 application that is designed using the [Flask](https://flask.palletsprojects.com/en/) framework.  
where users can register, login, . 
The application follows a **Model - View ** design pattern having components developed using Flask  
(ie Python for back-end), SQL database to act as the model and finally the front-end developed
using html css and javascript with the help of frameworks like Bootsrap 4 and more.

### My project consists of 3 web pages. These pages are inside the templates file
 
#### -1-sign up
 
#### -2- login
 
#### -3-home

```
/app
    - views.py
    - models.py
    - auth.py
    - __init__.py
    /services
        - main.py
    /templates
        - base.html
        - home.html
        - login.html
        - sign_up.html
    
   /static
       - index.js
   /styles
       - mainpage.css
```

The front end is written mostly in Python with some libraries built in for things like coding libraries, hashing passwords, 
 
 and checking and matching hash passwords at login.

I also added the SQLAlchemy toolkit
 
Which gives application developers the complete power and flexibility of SQL.
 
## Model
For the model, I have used a Structured Query Language or SQL database named ```database.db```. 
It is a relational database management system consisting of 2
tables namely
 information, users. 
These tables and their respective fields can be viewed using the command .schema under sqlite3 (an example). 
Every users being unique have their own ids which act as primary keys aer nd these keys 
so as to facilitate easy data management across tables.
 
SQLAlchemy provides a full suite of well known enterprise-level persistence patterns, designed for efficient
 
 and high performing database access, 
 
 adapted into a simple and Pythonic domain language.
 
 ## More on Flask
As mentioned earlier, the framework implies the use of a certain structure of directory/file listing as shown below:

static / contains all the static files like , javascript files & styles /```mainpage.css```.


templates/ 
contains all the html files used to implement the webpages with a ```base.html```  file acting as the base for other files.
```database.db``` is the database used to store all data .

```app.py``` and ```auth.py``` and  ```main.py``` and are the files handling the server and responding 
 
 to get and post requests made to it 
Responsible for the database
```models.py``` .
requirements.txt is a text file which contains the names of additional libraries / software that may be required to host and run the application.
By default, flask run command starts flask's built in webserver and runs it on localhost. 
 
 Using flask run -- http://127.0.0.1:5000/ changes it to run on all your machine's IP addresses.
 
Now when you are able to log in, you will be able to keep all the notes and ideas that were in your mind and refer to them 
 
 at all times and from anywhere because they are stored on the site.

This is my final project and this was cs50.

  #### Made by:
  # CS50 2022
  Hadji Rami, Algeria
  
