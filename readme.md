# Tally Code Brewers Hackathon 2021 URL Shortner
Web service to shorten urls alongwith statistics of shortened url clicks in the past 30 days.

# Steps to setup the project on your local machine
1. Clone the repo.
2. Install Python on your machine.
3. Run the following commands on the terminal

     ```pip install virtualenv```
   
     ```python -m venv env```
     
     ```.\env\Scripts\activate```
   
     ```pip install -r requirements.txt```
     
     ```python manage.py makemigrations```
     
     ```python manage.py migrate```
   
     ```python manage.py runserver``` //This is for running the site locally
     
4. A link http://127.0.0.1:8000/ will be generated. ctrl+click on it. The site will open in the browser.
