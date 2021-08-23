Creating Virtual Environment:

--> pip install virtualenv
--> virtualenv env(name)
--> env\scripts\activate   (activate the virtual env)
--> env\scripts\deactivate

Install requirements in the Env:

--> pip install django
--> pip list


Django Commands

Create an Apps:
--> django-admin startproject devplus(name of the project)

1. register the apps into the settings.py(Installed_Apps)
2. Create apps urls.py and define the views.py.
3. Include the path of apps urls.py into the main urls.py(root)urls
4. Now, start work in views.

Creating Templates:

Note: [ We will create folder to store our templates. 
        The templates will render into the views.py.]

1. Create the folder named templates (could be any name)
2. Now we need django to find these templates.
3. In settings.py, import os
4. settings.py -> TEMPLATES -> 'DIRS' -> add the file path (os.path.join(BASE_DIR, 'templates')
5. Now go to views.py and import render and create method to render templates files.                                                           


![Image of Yaktocat](https://github.com/pritom02bh/Django_Snippet/blob/main/Untitled-1.png)
