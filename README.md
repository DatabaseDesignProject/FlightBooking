# Airline-Management-System

This is a Django project which I have done as a part of the course **BITS- DATABASE SYSTEMS**.

This is a simple application in which you can manage flights ticketing data, see the details about the flights and the passengers who are aboard.

## Project Setup

Once you get the remote version on your device, open your terminal and follow the below steps :


- Create Venv 

  ```create virtual env
  $ python3 -m venv venv   
  ```

  '''activate venv
  $source venv/bin/activate
  '''

- Install project requirements from requirements.txt
  
  pip3 install -r requirements.txt

- Change Directory 

  ```change directory
  $ cd airline
  ```

- Get the server running

  '''migrate
  $ python3 manage.py migrate  
  '''
  ```runserver
  $ python3 manage.py runserver
  ```

## Apps in this project

#### flights
This app will keep track of all the flights available and the specific route will display all the flights and on clikcing the flight you will be shown the details of that particular flight. Here we can even add passengers to a flight.

#### users
In this app users can login to check their details and the flights which they are on. Additionally they can even book flights from here. I implemented this to learn how authentication works in django.

#### admin 
This is a route where you can login and see the data about all the models (Flights, Users and Airports) and you can add or delete certain data. 

For simplicity I used :

- username : admin
- password : admin

so that you guys can check it out and add or delete data to see how the changes are shown in the website.