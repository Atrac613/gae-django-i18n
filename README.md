GAE Django I18N Sample Code
=============

GAE SDK for Python version: 1.5.4

django version: 0.96

If mac user
------

$ sudo easy_install django

$ sudo port install gettest

Localization
-------

$ cd src/

$ mkdir conf/locale

$ django-admin.py makemessages -l en

$ django-admin.py makemessages -l ja

$ vi conf/locale/ja/LC_MESSAGES/django.po

$ django-admin.py compilemessages

Templates
-------

1. Load i18n
{% load i18n %}
2. Trans
{% trans "Hello!" %}
