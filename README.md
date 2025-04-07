# miniproject4Churong-David-Wei

# Discription
The code builds up a web app using django, the website has 5 pages in total, including a register login system.

# How to install required libraries
run in terminal: pip install -r requirements.txt

# How to use this program
Run the following commands in terminal of the directry where manage.py is:
# Create migration files
python manage.py makemigrations
# Apply the migrations to the database
python manage.py migrate
# Create a superuser for the admin site
python manage.py createsuperuser
# Run the server
python manage.py runserver

and the terminal will tell where the web app is, most likely 127.0.0.1:8000, open browser and go to that page
