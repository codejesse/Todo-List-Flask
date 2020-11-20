THIS IS THE DEMO FOR A TODO-LIST WEB APPLICATION USING PYTHON AND FLASK:


The web application includes a template file, this makes use of the Flask jinja template
--Layout.html : This is the main html template where the other html files gets html structure to avoid repitiion and waste of time
--add.html: This is the html file that displays a text field for the user to input a task
-- tasks.html: This is the index page which shows all the tasks the user has entered
-- task.py: This contains the python code for the web application it holds up all the logic.
........................How to run the web application.....................................
Flask runs a development server which call your application.py and the html components in order to run on a web browser
USING WINDOWS?
N/B: You must have python installed in your machine visit visit www.python.org to install
Step 1: open up your powershell or command prompt and type
pip install virtualenv
Step 2: once you have virualenv you need a virtualenvwrapper-win since its a windows machine
pip install virtualenvwrapper-win
Step3: Install flask
pip install flask

..................Running the project..................
open your powershell prompt and enter
setx FLASK_APP = task.py
FlaskExample> python -m flask run

This will run the application on a development server the link to the localhost will be generated