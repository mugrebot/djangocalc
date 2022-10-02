# This is a simple calculator using html, django, and javascript
## note that some of these steps required some workarounds on my end (m1 chips are the best!)

# To start create a virtual environment:

conda create --name calc_env python=3.8

then run it: 

conda activate calc_env

# Using command "pip freeze > requirements.txt" we can create a folder that we can install from using this command:

pip install -r requirements.txt

from there we should be good to go! 

# we will run the following commands: 

python manage.py runserver

Then we can visit the site running at - http://127.0.0.1:8000

From here, any calculations will render to http://127.0.0.1:8000/calculator

