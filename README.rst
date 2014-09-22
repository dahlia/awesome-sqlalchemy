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

SQLAlchemy-Continuum_
   Versioning and auditing extension for SQLAlchemy.

   - Creates versions for inserts, deletes and updates.
   - Does not store updates which don't change anything.
   - Supports alembic migrations.
   - Can revert objects data as well as all object relations at given
     transaction even if the object was deleted.
   - Transactions can be queried afterwards using SQLAlchemy query syntax.
   - Query for changed records at given transaction.
   - Temporal relationship reflection. Version object's relationship show
     the parent objects relationships as they where in that point in time.
   - Supports native versioning for PostgreSQL database (trigger based
     versioning).

SQLAlchemy-ORM-tree_
   An implementation for SQLAlchemy-based applications of
   the nested-sets/modified-pre-order-tree-traversal technique for
   storing hierarchical data in a relational database.

.. _SQLAlchemy-Continuum: https://sqlalchemy-continuum.readthedocs.org/
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


Dialects
--------

redshift_sqlalchemy_
   Amazon Redshift dialect for SQLAlchemy.

sphinxalchemy_
   SQLAlchemy dialect for iterfacing with Sphinx search engine via
   SphinxQL.

.. _redshift_sqlalchemy: https://github.com/binarydud/redshift_sqlalchemy
.. _sphinxalchemy: https://sphinxalchemy.readthedocs.org/


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

FormAlchemy_
   FormAlchemy eliminates boilerplate by autogenerating HTML input fields from a
   given model. FormAlchemy will try to figure out what kind of HTML code should
   be returned by introspecting the model's properties and generate ready-to-use
   HTML code that will fit the developer's application.

WTForms-Alchemy_
   WTForms-Alchemy is a WTForms_ extension toolkit for easier creation of
   model based forms.  Strongly influenced by Django ModelForm.

.. _Colander: http://docs.pylonsproject.org/projects/colander/
.. _ColanderAlchemy: https://github.com/stefanofontanelli/ColanderAlchemy
.. _Deform: http://docs.pylonsproject.org/projects/deform/
.. _FormAlchemy: http://formalchemy.org/
.. _WTForms: https://wtforms.readthedocs.org/
.. _WTForms-Alchemy: https://wtforms-alchemy.readthedocs.org/


Full-text Searching
-------------------

SQLAlchemy-Searchable_
   Full-text searchable models for SQLAlchemy. Only supports PostgreSQL.

.. _SQLAlchemy-Searchable: https://sqlalchemy-searchable.readthedocs.org/


GIS and Spatial Databases
-------------------------

GeoAlchemy_
   GeoAlchemy provides extensions to SQLAlchemy to work with spatial databases.

   The current supported spatial database systems are PostGIS_, Spatialite_,
   MySQL, Oracle, and MS SQL Server 2008.

`GeoAlchemy 2`_
   GeoAlchemy 2 provides extensions to SQLAlchemy for working with
   spatial databases.

   GeoAlchemy 2 focuses on PostGIS_.  PostGIS 1.5 and PostGIS 2 are supported.

   GeoAlchemy 2 aims to be simpler than its predecessor, GeoAlchemy_.
   Simpler to use, and simpler to maintain.

.. _GeoAlchemy: https://geoalchemy.readthedocs.org/
.. _GeoAlchemy 2: https://geoalchemy-2.readthedocs.org/
.. _PostGIS: http://postgis.refractions.net/
.. _Spatialite: http://www.gaia-gis.it/spatialite/


Internationalizations
---------------------

SQLAlchemy-i18n_
   Internationalization extension for SQLAlchemy models.


   - Stores translations in separate tables.
   - Reflects translation table structures based on
     parent model table structure.
   - Supports forcing of given locale.
   - Good performance (uses proxy dicts and other advanced SQLAlchemy
     concepts for performance optimization).

.. _SQLAlchemy-i18n: https://sqlalchemy-i18n.readthedocs.org/


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

pyramid_sqlalchemy_
  pyramid_sqlalchemy provides everything needed to use SQLAlchemy in
  Pyramid_ applications.
  
zope.sqlalchemy_
   The aim of this package is to unify the plethora of existing packages
   integrating SQLAlchemy with Zope_'s transaction management.
   As such it seeks only to provide a data manager and makes no attempt
   to define a zopeish way to configure engines.

.. _Flask: http://flask.pocoo.org/
.. _Flask-SQLAlchemy: https://pythonhosted.org/Flask-SQLAlchemy/
.. _Flask-SuperAdmin: https://github.com/syrusakbary/Flask-SuperAdmin
.. _Pyramid: http://www.pylonsproject.org/
.. _pyramid_sqlalchemy: https://pyramid-sqlalchemy.readthedocs.org
.. _Zope: http://www.zope.org/
.. _zope.sqlalchemy: https://pypi.python.org/pypi/zope.sqlalchemy
