# Getting Started

####

## Virtual Enviroment Setup
http://docs.python-guide.org/en/latest/dev/virtualenvs/

Install virtualenv: ```pip install virtualenv```

Make a new virtualenv in desired location: ```virtualenv hamath-workspace```

Activate the virtualenv: ```source /bin/activate```

and

Dectivate the virtualenv: ```deactivate```

## Setup Local Repository

pull down code from github with the following terminal commands:
```
git init
git remote add origin https://github.com/TheBigTeam/hamath
git pull origin master
```

## Project Setup

Install Requirements: ```pip install -r requirements.txt```

Run the server: python manage.py runserver

Open website in browser at http://localhost:8000 or admin at http://localhost:8000/admin (admin:admin)

