# Task-Tracker-Application

PROJECTFOLDER
  taskmanager
    taskmanager
      _pycache_
          (pyc files: init, settings, urls, wsgi)
      _init_.py
      asgi.py
      settings.py
      urls.py
      wsgi.py
    tasks
      _pycache_
          (pyc files: init, admin, apps, forms, models, urls, views)
      migrations
          _pycache_ 
              (init.pyc, 0001.pyc, 0002.c)
          __init__.py
          0001_initial.py
          0002_category_task_category.py
      templates/tasks
          task_form.html
          task_list.html
      __init__.py
      admin.py
      apps.py
      forms.py
      models.py
      tests.py
      urls.py
      views.py
    db.sqlite3
    manage.py
    
  Following difficulties with including branches, the layout of the files folders is above. Essentially, each standalone title with indented material under it is a folder. For example, PROJECTFOLDER/taskmanager contains the entire contents while the taskmanager below it contains all files/folders up to the tasks folder. 

  This system uses python, html, django, and sqlite (for a database). To run this system, one must install python and django and start the django server through their terminal. Following this, create the settings.py file, database, and migrate the files. Finally, you may construct other files like manage.py, models.py, and forms.py. Do not forget to save all files and do a final migration before running the server!
