# assignmentapi
Kartoza

The following outline the project development steps;

1. Firstly, from terminal, create file for your project , pip install django, pip install djangorestframework.
   Also from terminal create project using the django-admin command (startproject) and then also create app using the manage.py command(startapp)

2. THE PROJECT ARCHITECTURE:
    1. Created the admid mode using django admin
    2. Created the user model using the django model
    3. Map the from the app container urls to their respective views
    4. Used django forms to collect user data for onboarding
    5. Adopted python plain location to get users location

3. To create a superuser, you would have to run the "create superuser" command from terminal and enter credentials
   1. The admin can create users
   2. The admin has a log for all user activities.
   
4. Users can only see their profile and not the profile of others.
5. There is a list of users by their location.
