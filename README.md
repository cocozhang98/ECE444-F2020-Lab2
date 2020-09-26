# ECE444-F2020-Lab2

## Coco Zhang 1002084406
this repo is a clone of https://github.com/miguelgrinberg/flasky

## Activity 1
![Alt text](A1.png?raw=true "Screenshot for Activity 1")

## Activity 2
![Alt text](A2.png?raw=true "Screenshot for Activity 2")

## Activity 3
There are 4 context globals in flask. These enables Flasks to make the variables globally accessible to all threads (without interfering with other threads). There are 2 contexts in flasks each with 2 global variables (application context and request context).  
1. current-app (application context) is the instance of the active application. 
2. g (application context) can be used by the application for temporary storage when handling a request. 
3. request (request context) is the request object (the HTTP request sent by client) 
4. session (request context) is the user session - a global dictionary for storing values that are global between requests. 
