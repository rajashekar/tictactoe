# TicTacToe
Purpose of this project is to create TicTacToe game with Django. 

## Commands
### To create a virtual environment
```
python -m venv django-env
```

### To use the virutal environment
```
source django-env/bin/activate
```

### To install Django in above virtual environment
```
pip install django
```

### To create Django Project
```
django-admin startproject tictactoe
cd tictactoe
```

### To create super user
```
python manage.py createsuperuser
```

### To create apps inside the project
```
python manage.py startapp gameplay
python manage.py startapp player
```

### To get REPL in Django
```
python manage.py shell
```

### To start the server
```
python manage.py runserver
```

### To show migrations 
```
python manage.py showmigrations
```

### To make migrations
```
python manage.py makemigrations
```
Sample - 
```
Migrations for 'gameplay':
  gameplay/migrations/0004_auto_20200517_1232.py
    - Alter field by_first_player on move
Migrations for 'player':
  player/migrations/0002_auto_20200517_1232.py
    - Alter field message on invitation
    - Alter field to_user on invitation
```

### To run migration
```
python manage.py migrate
```
Sample - 
```
Operations to perform:
  Apply all migrations: admin, auth, contenttypes, gameplay, player, sessions
Running migrations:
  Applying gameplay.0004_auto_20200517_1232... OK
  Applying player.0002_auto_20200517_1232... OK
```