# BrightenUp

* This ecommerce app allows a user to choose items which will brighten up their day.  

* User persona:  The typical user is envisaged to be a woman in her 20s to 60s who is having a bad day!  The user wishes to brighten up their day and the app offers a variety of items for the user to purchase in order to do this.

* Technologies used:
* Virtual environment setup

[pipenv](https:\\pipenv.readthedocs.io)
A virtual environment was used at the start of the project.  This was installed using ```pip install pipenv```
Next thing I used the command ```pipenv install django```  to install django in my virtual environment
then I used ```pipenv shell``` to install the virutal environment in my django project.
Next I started a new django project inside my brightenup folder using the command ```django-admin startproject positivetimes .```
Next to check that everything was working I typed ```python manage.py runserver`` into the terminal and got the congratulations screen from django.
Then I did my first push to git using the following commands

1. ```git init```
2. then```git commit -m "first commit```
3. then ```git remote add origin https://github.com/debbiect246/brightenup.git```
4. then ```git push -u origin master```
I then created my store app using ```django-admin startapp store```
