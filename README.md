django-skel
===========

A modern Django (1.3.1) project skeleton.


Meta
====

* author: Randall Degges
* email:  rdegges@gmail.com
* status: maintained, in development
* notes:  Have feedback? Please send me an email. This project is still in its
          infancy, and will be changing rapidly.


Purpose
=======

For background, see: http://rdegges.com/deploying-django

Essentially--deploying Django projects is hard. There are lots of things you
need to take into consideration. Being a Django user for years, I believe I've
found some extremely useful patterns to help manage all sorts of Django sites
(from the very smallest apps, to the largest).

This project is meant to be a boilerplate project for starting development. It
is heavily opinionated in terms of services and tools--but I think the tradeoff
is worthwhile.


Docs
====

The full project documentation is hosted at RTFD: http://django-skel.rtfd.org/.
They are continuously updated to reflect changes and information about the
project, so be sure to read them before using this boilerplate.


Install
=======

django-skel currently supports Django 1.4. To create a new django-skel base
project, run the following command (this assumes you have Django 1.4 installed
already):

    $ django-admin.py startproject --template=https://github.com/rdegges/django-skel/zipball/master --name=Procfile woot

Where ``woot`` is the name of the project you'd like to create.

This is possible because Django 1.4's ``startproject`` command allows you to
fetch a project template over HTTP (which is what we're doing here).