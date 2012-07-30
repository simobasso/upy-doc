===============
Getting started
===============

This is the UPY tutorial.


Overview
============

**UPY** is intedeed to simplify the development of (web) applications with three different approaches. It provides:

* a list of ready-to-use contrib apps to install and enjoy with no code scripting, like 'image', 'newsletter', 'ckeditor';
 
* a list of contrib apps to use like a mini-framework to use in your models, admin or views to automate operations. For example the 'language' contrib gives you an admin to manage the languages, a model and admin to inherit for multilanguage support, a form to initialize in your views to easily get an html rendered object to use in your template with a select, links or flags.
    
* some usefull utility out of the contrib apps, like fields.CountryField to use in the admin, the uwsgidecorators to let you communicate with uwsgi application server etc.

We assume that you will already *perfectly* know the **Django Framework** and **Python language**. If you don't, here are all the refences you need:
 * **Python**: `Official Python tutorial`_
 * **Python**: `Dive into Python`_
 * **Django**: `Official Django documentation`_

Those resources will be excellent reading material if you are not familiar
with Python or Django. The Django tutorial is especially important as many
core Pinax concepts are simply ones you find in Django.

.. _Official Python tutorial: http://docs.python.org/tutorial/
.. _Dive into Python: http://diveintopython.net/
.. _Official Django documentation: http://docs.djangoproject.com/


Install
=======

Prerequisites for the last stable release:

- python 2.6
- django 1.4::
    
    pip install django
    
- django-mptt and django-imagekit (with PIL library) are required respectively for the tree and image contrib::

    pip install django-mptt django-imagekit

  but the upy.py scripts will give you an easy way to install everything you need in your `virtualenv`_

.. _virtualenv: http://www.virtualenv.org/en/latest/index.html

Last but not least, install upy **(TODO)**::

    pip install django-upy
    
or get it from our repository: http://upyproject.com

Tutorial
========

.. toctree::
   :maxdepth: 2
   
   tutorial

   
