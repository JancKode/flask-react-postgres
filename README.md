# React Flask login boilerplate

# How to run the app

1. Make sure Pyhon, posgressql and nodejs are installed in your system

2. Install pipenv 
   
     `pip install pipenv`
   
3. Open terminal and go to project directory

4. Launch virtual environment
  
    `pipenv shell`
  
5. Install flask and python dependencies

    `pipenv install requirements.txt`
    
6. Open a new terminal and launch posgres server 

   `systemctl start posgresql-12`
   
7. Change dabase URI in __init__.py

   `postgresql://<dbusername>:<password>@localhost/<database name>`
  
7. Launch flask app

     `export FLASK_APP=__init__`
   
     `export FLASK_DEBUG=1`
   
     `flask run`
     
8. Check the server 

   `http://127.0.0.1:5000/`
   
7. Open a new terminal and change directory to frontend

8. Install React dependencies

     `npm install`
   
9. Run React app

     `npm start`
