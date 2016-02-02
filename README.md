# Getting Started

####

## Virtual Enviroment Setup
http://docs.python-guide.org/en/latest/dev/virtualenvs/

Install virtualenv: ```pip install virtualenv```

Make a new virtualenv in desired location: ```virtualenv hamath-workspace```

Activate the virtualenv: ```source /bin/activate```

The virtualenv can be deactivated: ```deactivate```

## Setup Local Repository

Now, from inside our activated virtual enviroment 'hamath-workspace', pull down code from github with the following terminal commands:
```
git init
git remote add origin https://github.com/TheBigTeam/hamath
git pull origin master
```
You will get two projects: <hamath> and <mysite-example>

## Project Setup

Install Requirements: ```pip install -r requirements.txt```

Navigate to: ```/hammath-workspace/hamath/hamath```

Run the server: ```python manage.py runserver```

Open website in browser at http://localhost:8000 or admin at http://localhost:8000/admin (admin:admin)

