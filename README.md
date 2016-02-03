# Mac Setup

***

**First things first, make sure you have pip, python, and github installed and working properly. If not, don't sweat it, check out the wiki for installation instructions**

***

## Virtual Enviroment Setup

**wiki link:** *https://github.com/TheBigTeam/hamath-workspace/wiki/Installing-Virturalenv*

Make a new virtualenv in desired location: ```virtualenv hamath-workspace```

The ```hamath-workspace``` directory isolates our libraries and contains the local github repository.

**How To Use:**

Activate the virtualenv: ```source /bin/activate```

The virtualenv can be deactivated: ```deactivate```

## Setup Local Repository

Now, from inside our activated virtual enviroment (*hamath-workspace*), pull down code from github with the following terminal commands:
```
git init
git remote add origin https://github.com/TheBigTeam/hamath-workspace
git pull origin master
```
You will get two projects: 
* *hamath*: is the class project
* *mysite-example*: is a django sample website described here: https://docs.djangoproject.com/en/1.9/intro/tutorial01/

## Project Setup

Install Requirements: ```pip install -r requirements.txt```

Navigate to: ```/hammath-workspace/hamath/hamath```

Run the server: ```python manage.py runserver```

Open website in browser at http://localhost:8000 or admin at http://localhost:8000/admin (admin:admin)



