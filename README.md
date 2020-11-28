# Profiles REST API

Profiles REST API course code.

# In virtualenv.

1. vagrant up  
2. vagrant ssh  
3. cd /vagrant  
4. source ~/env/bin/activate  
5. pip install -r requirements.txt  
6. django-admin startproject profiles_project .  
7. python manage.py startapp profiles_api  
8. enable profiles_app in django project   
  - profiles_project/settings.py  
    - In settings.py add in INSTALLED_APPS  
      - rest_framework, rest_framework.authtoken, profiles_api  
9. python manage.py runserver 0.0.0.0:8000
10. test on local workstation: 127.0.0.1:8000 should show django project home  

