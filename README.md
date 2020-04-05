# About this project
------------------

Full Stack Firebase Web Blog App using NodeJs & Firebase - Dynamic Web App & Website Project - Complete Firebase for Web


# Description
-----------

A dynamic web app has been created, this is a Blog App using Firebase & Node.Js This blog project includes Firebase Web Authentication ,  Firebase Web Real Time Database , Firebase Web Storage and Firebase Web user Authentication using Firebase Authentication , Firebase Database , Firebase Forget Password and Firebase Reset Password.

 # What I have learn while developing this blog app
------------------------------------------------

Develod Dynamic Web Blog App using Firebase & NodeJs
Firebase Web Authentication, Firebase Web Realtime Database
Firebase Web Query Data from Firebase Database
Firebase Web Storage
Firebase user Authentication
Firebase Signin user and Firebase Signup user using Firebase Authentication
Firebase Forget Password and Firebase Reset Password.


# How to start?

## Firebase
--------
Create a firebase account
Create a new web project <> on firebase and followo the instructions from the following website
https://console.firebase.google.com/u/0/

## Create a new APP

- Firebase Web Authentication 
select Sign-in method and enable status of  Email/Password option

- Firebase Database
 Go to rules and change the rules from false to true for testing purposes
 
{
  "rules": {
    ".read": true,
    ".write": true
  }
}

## Node JS
------

Install Node JS and follow the instructions

https://nodejs.org/en/download/

- Create a new folder where you want to save your project


- open a terminal on yout mac or Command Prompt program on windowns
- navigate to your directory folder project run the following commands to see if node was installed properly

node --version
npm --version 

## Visual Code Editor
----------------

Download your favourite code editor, in this case I use visual code. https://code.visualstudio.com/download


Create the application
-------------------- 

On your terminal on mac or Command Prompt program navigate to your directory folder project run the following command to create an APP. 

Tyope the command below:

npm init


After answering all questions from a new file called {}package.json will be created. The file normally contains information of the APP. See example below.


{
  "name": "blog_app",
  "version": "1.0.0",
  "description": "",
  "main": "/jsindex.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/jaimehernan95/qcprojectv1.git"
  },
  "keywords": [
    "node"
  ],
  "author": "Jaime Hernan",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/jaimehernan95/qcprojectv1/issues"
  },
  "homepage": "https://github.com/jaimehernan95/qcprojectv1#readme",
  "dependencies": {
    "http-server": "^0.12.1"
  }
}


INDEX.JS
--------

Create a new file called index.js

Inside the file type the code below  and save it

console.log ( "hello ");

INDEX.HTML
---------

Create a new Html page and save it.

HTTP-SERVER
----------

we need http-server to run all components that are needed to run the application in the local servert. Type the following command to install it

npm install http-server -g

Testing
-------
go to your project directory and run the following command

http-server

the response should be

Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080

Copy and paste the address above on a browser to see the results.


The entire projects is available in the link below it is CRUD project.

https://github.com/jaimehernan95/qcprojectv1/

## @ 2020 - april 05. minimist bug  fixed
source: https://www.npmjs.com/package/minimist

install
With npm do:
npm install minimist
--------- Bug Fixed line ends here ----------
