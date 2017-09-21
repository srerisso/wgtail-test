
Setup de wagtail server (muy parecido al setup de Django server).

1. Para arrancar wagtail server
> python manage.py runserver $IP:$PORT

Hay que añadir a ALLOWED-HOSTS a settings.py (en settings/base.py)

2. Tutorial de 10 minutos de wagtail en http://docs.wagtail.io/en/latest/getting_started/tutorial.html?_ga=2.224159195.1362631352.1505920718-2029111624.1505920718

2.1 Run 
- python manage.py makemigrations, 
then 
python manage.py migrate 

to update the database with your model changes. You must run the above commands each time you make changes to the model definition.