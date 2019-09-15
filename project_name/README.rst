===============================
project_name
===============================

.. image:: https://badge.fury.io/py/project_name.png
    :target: http://badge.fury.io/py/project_name

.. image:: https://pypip.in/d/project_name/badge.png
    :target: https://crate.io/packages/project_name?version=latest


project_name website

* Free software: BSD license

Requirements
------------

* Django 1.10+
* Python 2.7
* Django CMS 3.4+

.. _django-cms: https://github.com/divio/django-cms

Installation
----------------------------

#. Clone the git repository.
#. Create a production.py file in project_name/project_name/project_name/settings by copying what's in the example_production.py
    * Fill database details in the file you just created
    * Add the site admins in the ADMINS variable
    * Add server host in ALLOWED_HOSTS

#. Install all third party packages by running::

    $ pip install -r requirements/development.txt

#. Apply migrations::

    $ python manage.py migrate

