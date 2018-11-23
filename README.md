# start django
virtualenv venv  
source venv/bin/activate
cd mysite      
python manage.py runserver

# setup env

pip install virtualenv

virtualenv venv

source venv/bin/activate

pip install Django==1.8.1

pip freeze > requirements.txt

pip install -r requirements.txt


# setup django app

django-admin startproject mysite

cd mysite 
//setup myapp
python manage.py startapp myapp

//setup database
python manage.py migrate

python manage.py runserver




# reference
[1] [Django Intro Tutorial! Build a website in 11 mins](https://www.youtube.com/watch?v=PqeAvFf_HDI)      
[2] [startbootstrap](https://startbootstrap.com/)
