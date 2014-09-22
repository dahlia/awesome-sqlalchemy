Awesome SQLAlchemy
==================

A curated list of awesome extra libraries for SQLAlchemy_.  Inspired by
awesome-python_.

.. _SQLAlchemy: http://www.sqlalchemy.org/
.. _awesome-python: https://github.com/vinta/awesome-python

Licensed under a `Creative Commons Attribution-ShareAlike 4.0 International
License`__.

__ http://creativecommons.org/licenses/by-sa/4.0/

.. contents:: Table of Contents
   :backlinks: none


Data Structures
---------------

SQLAlchemy-ORM-tree_
   An implementation for SQLAlchemy-based applications of
   the nested-sets/modified-pre-order-tree-traversal technique for
   storing hierarchical data in a relational database.

.. _SQLAlchemy-ORM-tree: https://sqlalchemy-orm-tree.readthedocs.org/


Data Types
----------

SQLAlchemy-Utils_
   Various utility functions, new data types and helpers for SQLAlchemy.

.. _SQLAlchemy-Utils: https://sqlalchemy-utils.readthedocs.org/


Database Migration Tools
------------------------

Alembic_
   Alembic is a lightweight database migration tool for usage with the
   SQLAlchemy Database Toolkit for Python.

sqlalchemy-migrate_
   Inspired by Ruby on Rails' migrations, SQLAlchemy Migrate provides
   a way to deal with database schema changes in SQLAlchemy projects.

.. _Alembic: https://alembic.readthedocs.org/
.. _sqlalchemy-migrate: https://sqlalchemy-migrate.readthedocs.org/


File/Image Attachments
----------------------

SQLAlchemy-ImageAttach_
   SQLAlchemy-ImageAttach is a SQLAlchemy extension for attaching images
   to entity objects.

.. _SQLAlchemy-ImageAttach: https://sqlalchemy-imageattach.readthedocs.org/


Forms and Data Validations
--------------------------

ColanderAlchemy_
   ColanderAlchemy helps you to auto-generate Colander_ schemas that are based
   on SQLAlchemy mapped classes.

   Such Colander schemas can be used with libraries like Deform_ and helps
   remove the need for duplication of schema definitions.

WTForms-Alchemy_
   WTForms-Alchemy is a WTForms extension toolkit for easier creation of
   model based forms.  Strongly influenced by Django ModelForm.

.. _Colander: http://docs.pylonsproject.org/projects/colander/
.. _ColanderAlchemy: https://github.com/stefanofontanelli/ColanderAlchemy
.. _Deform: http://docs.pylonsproject.org/projects/deform/
.. _WTForms-Alchemy: https://wtforms-alchemy.readthedocs.org/


Profilers
---------

SQLTap_
   SQLTap is a library that allows you to profile and introspect the queries
   that your application makes using SQLAlchemy.

   SQLTap helps you understand:

   - how many times a sql query is executed
   - how much time your sql queries take
   - where your application is issuing sql queries from

.. _SQLTap: https://github.com/inconshreveable/sqltap


Web Framework Integrations
--------------------------

Flask-SQLAlchemy_
   Flask-SQLAlchemy is an extension for Flask_ that adds support for
   SQLAlchemy to your application.

Flask-SuperAdmin_
   The admin interface framework for Flask_.
   With scaffolding for SQLAlchemy, MongoEngine and Django.

zope.sqlalchemy_
   The aim of this package is to unify the plethora of existing packages
   integrating SQLAlchemy with Zope's transaction management.
   As such it seeks only to provide a data manager and makes no attempt
   to define a zopeish way to configure engines.

.. _Flask: http://flask.pocoo.org/
.. _Flask-SQLAlchemy: https://pythonhosted.org/Flask-SQLAlchemy/
.. _Flask-SuperAdmin: https://github.com/syrusakbary/Flask-SuperAdmin
.. _Zope: http://www.zope.org/
.. _zope.sqlalchemy: https://pypi.python.org/pypi/zope.sqlalchemy
