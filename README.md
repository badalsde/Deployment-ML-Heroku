# ML-Model-Flask-Deployment
This is my first project deployed on production using Flask API on Heroku.

Project Structure
This project has four major parts :

1. app.py - This contains Flask APIs that receives house details through GUI or API calls, computes the precited value based on 
            our model and returns it.
2. templates - This folder contains the HTML template to allow user to enter house detail and displays the predicted house price.

## Initialize the folder with requirements.txt and a Procfile:

Procfile:

web: gunicorn app:app

Requirements:

#run this

pip freeze > requirements.txt


