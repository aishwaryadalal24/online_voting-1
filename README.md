# online_voting
online voting system with django with data security using homomorphic encryption algorithm

# Setup :

1) Create a folder and put all the files inside it.
2) Create a virtual environment = - virtualenv env
3) Activate VirtualENV = source env/bin/activate
4) Run requirements.txt = pip install r requirements.txt
5) Run Migrations Command = 
    i) python manage.py makemigrations
    ii) python manage.py migrate
6) Run the Application = python manage.py runserver
7) On the day of result edit the views.py files in members folder , erase the "not announced" string and write the strings in commented section so that viewrs can view result of voting.
