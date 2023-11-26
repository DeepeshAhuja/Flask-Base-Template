# Introduction
This is a base template of flask. Which has maintained the flask directory tree structure.

# How to use
Run the following commands in your terminal
## create a virtual Environment
```
python3 -m venv venv
```
## activate the virtual Environment
```
source venv/bin/activate
```
## and to deactivate the virtual environment
```
deactivate
```
## clone the repo
```
git clone "https://github.com/DeepeshAhuja/Flask-Base-Template"
```
## install the requirements
```
pip install -r requirements.txt
```
## run the app
```
python3 app.py
```
# Note:-
## You can add HTML files inside templates folder
### you can use index.html code in your other html files. This is the basic skeleton for html
```
Inside the 
{%block title%} 

{% endblock %} 
block it will automatically render inside title tag for that html page
```
```
Simillarly if you write inside the 
{%block head%} 

{% endblock %} 
block it will automatically render inside head tag for that html page
```
```
Simillarly if you write inside the 
{%block body%} 

{% endblock %} 
block it will automatically render inside body tag for that html page
```
## You can add CSS files inside static folder
### If you want to link css file inside html:
```
Inside the html file write this code
<link rel="stylesheet" href="{{url_for('static',filename='css/filename.css')}}">
(or)
<link rel="stylesheet" href="../static/css/filename.css">
```
## You can add JS files inside static folder
## You can add images inside static folder
## You can add other files inside static folder