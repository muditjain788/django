# Installing Django

$ python -m django --version

# creating a project
$ django-admin startproject mysite
This will create a mysite directory in your current directory
Let’s look at what this has created:
- mysite/
   - manage.py
   - mysite/
      -  __init__.py
      - settings.py
      -  urls.py
      -  wsgi.py
 
## These files are

    * mysite/ :-is root directory is just a container for your project.you can rename it to anything you like.
    
    * manage.py: A command-line utility that lets you interact with this Django project in various ways. 
                
    * mysite/:-The inner mysite/ directory is the actual Python package for your project. 
               Its name is the Python package name you’ll need to use to import anything inside it (e.g. mysite.urls).
               
    * mysite/__init__.py: An empty file that tells Python that this directory should be considered a Python package.
    
    * mysite/settings.py: Settings/configuration for this Django project. 
                          Django settings will tell you all about how settings work.
    * mysite/urls.py: The URL declarations for this Django project; a “table of contents” of your Django-powered site. 
   
    * mysite/wsgi.py: An entry-point for WSGI-compatible web servers to serve your project. 
   
 
