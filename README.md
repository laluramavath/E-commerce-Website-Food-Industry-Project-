Step1: Download and Install Node JS Run Environment

check in the cmd
node -v
npm -v

step2:creating JSON files

npm Install
>>package.lock.json file created

npm init -y
>>package.json file created

step3:Creating node_modules

npm i --save express
>>express package installed

npm Install ejs --save
//this is gonna allow pass data to the html

npm Install --save request

npm Install --save request


Step3: Project Folder Structure:
File:
index.js(starting point of the file)

Folder:
public:
    ->css->main.css
    ->js->script.js
    ->img
views:
    ->Pages->all html files

step4:
  Install XAMPP
  start the Apache(responsible for serving web pages to clients over HTTPS
  start MYSQL(for database)


Step4:
index.js, will be the file which is going to connect everything in the Project

It will deliver the HTML to the user, so that the user will be able to interact with the apllication.

Now, we need to create a server because the purpose of using Node Js, is to create the server
So to create the server, we are going to use express
So we will import express
and create an server

Step5:
We need to deliver the HTML to the user.
so we need to render an HTML page instead of just an random message.


Step7:
Test HTML
