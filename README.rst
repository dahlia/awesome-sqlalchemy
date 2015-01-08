Awesome SQLAlchemy
==================

A curated list of awesome extra libraries and resources for SQLAlchemy_.  Inspired by
awesome-python_.  (See also other `awesome lists`__!)

Licensed under a `Creative Commons Attribution-ShareAlike 4.0 International
License`__.

.. _SQLAlchemy: http://www.sqlalchemy.org/
.. _awesome-python: https://github.com/vinta/awesome-python
__ https://github.com/sindresorhus/awesome
__ http://creativecommons.org/licenses/by-sa/4.0/

.. contents:: Table of Contents
   :backlinks: none
   :depth: 3


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

sqlalchemy_mptt_
   Library for implementing MPTT (modified preorder tree traversal) with
   SQLAlchemy models and working with trees of model instances,
   like django-mptt_.

SQLAlchemy-ORM-tree_
   An implementation for SQLAlchemy-based applications of
   the nested-sets/modified-pre-order-tree-traversal technique for
   storing hierarchical data in a relational database.

vdm_
   Versioned domain model. Python library for revisioning/versioning of databases.

.. _django-mptt: https://github.com/django-mptt/django-mptt/
.. _SQLAlchemy-Continuum: https://sqlalchemy-continuum.readthedocs.org/
.. _sqlalchemy_mptt: https://sqlalchemy-mptt.readthedocs.org/
.. _SQLAlchemy-ORM-tree: https://sqlalchemy-orm-tree.readthedocs.org/
.. _vdm: https://github.com/okfn/vdm


Data Types
----------

SQLAlchemy-Utils_
   Various utility functions, new data types and helpers for SQLAlchemy

   - Listeners
   - Data types: {..., ChoiceType, CountryType, JSONType, URLType, UUIDType, ...}
   - Range data types
   - Aggregated attributes
   - Generates decorator
   - Generic relationships
   - Database helpers: create_database, drop_database
   - Foreign key helpers
   - ORM helpers
   - Utility classes
   - Model mixins: Timestamp (created, updated times)

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

http://docs.sqlalchemy.org/en/latest/dialects/

redshift_sqlalchemy_
   `Amazon Redshift`_ dialect for SQLAlchemy.

sphinxalchemy_
   SQLAlchemy dialect for iterfacing with Sphinx_ (search engine) via
   SphinxQL.

.. _Amazon Redshift: https://aws.amazon.com/redshift/
.. _redshift_sqlalchemy: https://github.com/binarydud/redshift_sqlalchemy
.. _Sphinx: http://sphinxsearch.com/
.. _sphinxalchemy: https://sphinxalchemy.readthedocs.org/


Documentation
---------------

* http://docs.sqlalchemy.org/en/latest/
* http://docs.sqlalchemy.org/en/latest/intro.html
* http://docs.sqlalchemy.org/en/latest/core/tutorial.html
* http://docs.sqlalchemy.org/en/latest/orm/tutorial.html
* http://docs.sqlalchemy.org/en/latest/glossary.html


File and Image Attachments
--------------------------

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
.. _FormAlchemy: https://github.com/FormAlchemy/formalchemy
.. _WTForms: https://wtforms.readthedocs.org/
.. _WTForms-Alchemy: https://wtforms-alchemy.readthedocs.org/


Full-text Searching
-------------------

SQLAlchemy-Searchable_
   Full-text searchable models for SQLAlchemy. Only supports PostgreSQL.

.. _SQLAlchemy-Searchable: https://sqlalchemy-searchable.readthedocs.org/

SQLAlchemy-FullText-Search_
   Fulltext search support with MySQL & SQLAlchemy.

.. _SQLAlchemy-FullText-Search: https://github.com/mengzhuo/sqlalchemy-fulltext-search


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

flask_debugtoolbar_
   Debug toolbar with SQLAlchemy query information for Flask.

pyramid_debugtoolbar_
   Debug toolbar with SQLAlchemy query information for Pyramid.

SQLTap_
   SQLTap is a library that allows you to profile and introspect the queries
   that your application makes using SQLAlchemy.

   SQLTap helps you understand:

   - how many times a sql query is executed
   - how much time your sql queries take
   - where your application is issuing sql queries from

.. _flask_debugtoolbar: https://github.com/mgood/flask-debugtoolbar
.. _pyramid_debugtoolbar: https://github.com/Pylons/pyramid_debugtoolbar
.. _SQLTap: https://github.com/inconshreveable/sqltap


Recipes
-------

* https://bitbucket.org/zzzeek/sqlalchemy/wiki/UsageRecipes


Testing
-------

charlatan_
   Fixtures management for SQLAlchemy and other systems.

factory_boy_
   Generate fake data and create random fixtures for testing in SQLAlchemy
   and many other Python ORM systems.

mixer_
   Generate fake data and create random fixtures for testing in SQLAlchemy
   and many other Python ORM systems.


.. _charlatan: https://github.com/uber/charlatan
.. _factory_boy: https://github.com/rbarrois/factory_boy
.. _mixer: https://github.com/klen/mixer


Thin Abstractions
-----------------

Dataset_
   Easy-to-use data handling for SQL data stores in Python with support for
   implicit table creation, bulk loading, and transaction. Dataset also
   includes support for freezing data to CSV and JSON flat files.

rdflib-sqlalchemy_
   RDFLib_ store using SQLAlchemy dbapi as back-end.

SQLSoup_
   SQLSoup provides a convenient way to map Python objects to
   relational database tables, with no declarative code of any kind.
   It's built on top of the SQLAlchemy ORM and provides a super-minimalistic
   interface to an existing database.

.. _Dataset: https://dataset.readthedocs.org/
.. _RDFLib: https://github.com/RDFLib/rdflib
.. _rdflib-sqlalchemy: https://github.com/RDFLib/rdflib-sqlalchemy
.. _SQLSoup: https://sqlsoup.readthedocs.org/



Vendor-specific Extensions
--------------------------

PostgreSQL
..........

sqlalchemy-crosstab-postgresql_
   New grammar for SQLAlchemy to make handling the ``crosstab()`` tablefunc
   (i.e. pivot tables) in PostgreSQL easy peasy.

.. _sqlalchemy-crosstab-postgresql:
   https://github.com/makmanalp/sqlalchemy-crosstab-postgresql


Visualizations
--------------

sadisplay_
   Simple package for describing SQLAlchemy schema and display raw database tables by reflecting feature.

sqlalchemy_schemadisplay_
   This module generates images from SQLAlchemy models.

.. _sadisplay: https://bitbucket.org/estin/sadisplay
.. _sqlalchemy_schemadisplay: https://github.com/fschulze/sqlalchemy_schemadisplay


Web
---

Framework Integrations
......................

bottle-sqlalchemy_
   A Bottle_ plugin to manage SQLAlchemy session to your application.

Flask-SQLAlchemy_
   Flask-SQLAlchemy is an extension for Flask_ that adds support for
   SQLAlchemy to your application.

Flask-Admin_
   The admin interface framework for Flask_.
   With scaffolding for SQLAlchemy, MongoEngine, pymongo and Peewee.

pyramid_sqlalchemy_
  pyramid_sqlalchemy provides everything needed to use SQLAlchemy in
  Pyramid_ applications.

pyramid_restler_
   pyramid_restler is a somewhat-opinionated toolkit for building
   RESTful Web services and applications on top of the
   Pyramid framework (with SQLAlchemy models).

sacrud_
   SACRUD will solve your problem of CRUD interface for SQLAlchemy,
   by providing extension for Pyramid_ (yet) or use it in pure form.
   Unlike classical CRUD interface, pyramid_sacrud_ allows override and
   flexibly customize interface (that is closer to ``django.contrib.admin``).

SQLAlchemy-Wrapper_
    A light and framework-independent wrapper for SQLAlchemy that makes
    it really easy to setup and use.

    - Doesn't change the SQLAlchemy syntax.
    - Can paginate the results of the queries.
    - Support for muliple databases at the same time.

zope.sqlalchemy_
   The aim of this package is to unify the plethora of existing packages
   integrating SQLAlchemy with Zope_'s transaction management.
   As such it seeks only to provide a data manager and makes no attempt
   to define a zopeish way to configure engines.

.. _Bottle: http://bottlepy.org/
.. _bottle-sqlalchemy: https://github.com/iurisilvio/bottle-sqlalchemy
.. _Flask: http://flask.pocoo.org/
.. _Flask-SQLAlchemy: https://pythonhosted.org/Flask-SQLAlchemy/
.. _Flask-Admin: https://github.com/mrjoes/flask-admin/
.. _Pyramid: http://www.pylonsproject.org/
.. _pyramid_restler: https://github.com/wylee/pyramid_restler
.. _pyramid_sacrud: https://pyramid-sacrud.readthedocs.org/
.. _pyramid_sqlalchemy: https://pyramid-sqlalchemy.readthedocs.org
.. _sacrud: https://sacrud.readthedocs.org/
.. _SQLAlchemy-Wrapper: https://github.com/lucuma/sqlalchemy-wrapper
.. _Zope: http://www.zope.org/
.. _zope.sqlalchemy: https://pypi.python.org/pypi/zope.sqlalchemy


Other
.....

paginate_sqlalchemy_
   This module helps dividing large lists of items into pages.
   The user is shown one page at a time and can navigate to other pages.

sandman_
   Generate a curl-able REST HTTP API with searching and filtering
   for all tables in a database and an admin UI with Flask-SQLAlchemy
   and HTTP Basic Authentication.

.. _paginate_sqlalchemy: https://github.com/Pylons/paginate_sqlalchemy
.. _sandman: https://github.com/jeffknupp/sandman
