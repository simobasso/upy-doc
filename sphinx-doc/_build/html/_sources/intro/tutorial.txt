Tutorial
============

1.Starting a Project
---------------------

To start a upy project you need to start a normal django project and replace the file you find in upy/bin/upy_project_set in the root.
You will overwrite:
* __init__.py
* manage.py
* settings.py
* urls.py
    
and copy:
* config.py
* django_wsgi.py
* upstream_errorpage.html
* upython.py
* uwsgi.ini
    
Otherwise, if you want upy do all this boring stuff, just go in the upy/bin directory and in the command line type::
    
    root:~/yourhome/upy/bin$ upy.py
    
and follow the instructions. It will set the projects as required and if needed, it will create the virtualenv for your project and so on.

2.Config and Settings
---------------------

The *only* configuration file you will change is :file:`config.py`.
You can set there the normal django settings like database, installed_apps, template dir, and set all the variables to initialize the upy apps you need.

.. note::

    You should set the *USE_APP* to True just if you want the ready-to-use application on your admin. If you just need to inherit the model/admin or use other functions you only have to import the right module.


3.Deploying
-----------

TODO

4.Cotrib.tree
-------------

    4.1 Models
    
    TODO
    
    4.2 Admin
    
    TODO
    
    4.3 Views
    
    TODO
    
    4.4 Template
    
    TODO
    
5.Cotrib.G11n
-------------

    4.1 Models
    
    TODO
    
    4.2 Admin
    
    TODO
    
    4.3 Views
    
    TODO
    
    4.4 Template
    
    TODO
