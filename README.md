# Awesome SQLAlchemy with stars

.. image:: <https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg>
:target: <https://github.com/sindresorhus/awesome> ⭐ 496,370 | 🐛 100 | 📅 2026-06-30

A curated list of awesome extra libraries and resources for SQLAlchemy\_.  Inspired by
awesome-python\_.  (See also other `awesome lists`\_\_!)

Licensed under a `Creative Commons Attribution-ShareAlike 4.0 International
License`\_\_.

.. \_SQLAlchemy: <https://www.sqlalchemy.org/>
.. \_awesome-python: <https://github.com/vinta/awesome-python> ⭐ 314,242 | 🐛 15 | 🌐 Python | 📅 2026-08-16
\_\_ <https://github.com/sindresorhus/awesome> ⭐ 496,370 | 🐛 100 | 📅 2026-06-30
\_\_ <https://creativecommons.org/licenses/by-sa/4.0/>

.. contents:: Table of Contents
:backlinks: none
:depth: 3

## Data Structures

bemi-sqlalchemy\_
Automatic data change tracking for SQLAlchemy.

* Automatically tracks PostgreSQL changes with application-specific context
* Captures data changes with 100% reliability, even if executed through direct SQL outside the application
* Doesn't affect code runtime execution performance and database workload
* Works without changing table structures, rewriting the code, and creating heavy database triggers
* Integrates with FastAPI

SQLAlchemy-Continuum\_
Versioning and auditing extension for SQLAlchemy.

* Creates versions for inserts, deletes and updates.
* Does not store updates which don't change anything.
* Supports alembic migrations.
* Can revert objects data as well as all object relations at given
  transaction even if the object was deleted.
* Transactions can be queried afterwards using SQLAlchemy query syntax.
* Query for changed records at given transaction.
* Temporal relationship reflection. Version object's relationship show
  the parent objects relationships as they where in that point in time.
* Supports native versioning for PostgreSQL database (trigger based
  versioning).

sqlalchemy\_mptt\_
Library for implementing MPTT (modified preorder tree traversal) with
SQLAlchemy models and working with trees of model instances,
like django-mptt\_.

SQLAlchemy-ORM-tree\_
An implementation for SQLAlchemy-based applications of
the nested-sets/modified-pre-order-tree-traversal technique for
storing hierarchical data in a relational database.

vdm\_
Versioned domain model. Python library for revisioning/versioning of databases.

.. \_bemi-sqlalchemy: <https://github.com/BemiHQ/bemi-sqlalchemy> ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2025-07-04
.. \_django-mptt: <https://github.com/django-mptt/django-mptt/> ⭐ 2,972 | 🐛 3 | 🌐 Python | 📅 2026-06-02
.. \_SQLAlchemy-Continuum: <https://sqlalchemy-continuum.readthedocs.io/>
.. \_sqlalchemy\_mptt: <https://sqlalchemy-mptt.readthedocs.io/>
.. \_SQLAlchemy-ORM-tree: <https://sqlalchemy-orm-tree.readthedocs.io/>
.. \_vdm: <https://github.com/okfn/vdm> ⭐ 43 | 🐛 6 | 🌐 Python | 📅 2021-01-12

## Data Types

SQLAlchemy-Enum34\_
SQLAlchemy type to store standard `enum.Enum` values.

SQLAlchemy-Utc\_
SQLAlchemy type to store aware `datetime.datetime` values.

SQLAlchemy-Utils\_
Various utility functions, new data types and helpers for SQLAlchemy

* Listeners
* Data types: {..., ChoiceType, CountryType, JSONType, URLType, UUIDType, ...}
* Range data types
* Aggregated attributes
* Generates decorator
* Generic relationships
* Database helpers: create\_database, drop\_database
* Foreign key helpers
* ORM helpers
* Utility classes
* Model mixins: Timestamp (created, updated times)

.. \_SQLAlchemy-Enum34: <https://github.com/spoqa/sqlalchemy-enum34> ⭐ 50 | 🐛 4 | 🌐 Python | 📅 2021-04-14
.. \_SQLAlchemy-Utc: <https://github.com/spoqa/sqlalchemy-utc> ⭐ 103 | 🐛 7 | 🌐 Python | 📅 2022-08-17
.. \_SQLAlchemy-Utils: <https://sqlalchemy-utils.readthedocs.io/>

## Database Migration Tools

Alembic\_
Alembic is a lightweight database migration tool for usage with the
SQLAlchemy Database Toolkit for Python.

alembic-git-revisions\_
Derives Alembic migration order from git commit history instead of a
hardcoded `down_revision`, so migrations created on parallel branches
never collide on merge and the `Multiple head revisions are present`
error stops happening.

sqlalchemy-migrate\_
Inspired by Ruby on Rails' migrations, SQLAlchemy Migrate provides
a way to deal with database schema changes in SQLAlchemy projects.

.. \_Alembic: <https://alembic.readthedocs.io/>
.. \_alembic-git-revisions: <https://github.com/Mergifyio/alembic-git-revisions> ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-08-14
.. \_sqlalchemy-migrate: <https://sqlalchemy-migrate.readthedocs.io/>

## Dialects

<https://docs.sqlalchemy.org/en/latest/dialects/>

redshift\_sqlalchemy\_
`Amazon Redshift`\_ dialect for SQLAlchemy.

sphinxalchemy\_
SQLAlchemy dialect for interfacing with Sphinx\_ (search engine) via
SphinxQL.

GINO\_
An asynchronous PostgreSQL dialect for asyncpg\_, providing SQLAlchemy
core support and its own asynchronous ORM interface.

.. \_Amazon Redshift: <https://aws.amazon.com/redshift/>
.. \_redshift\_sqlalchemy: <https://github.com/binarydud/redshift_sqlalchemy> ⭐ 48 | 🐛 4 | 🌐 Python | 📅 2015-12-07
.. \_Sphinx: <https://sphinxsearch.com/>
.. \_sphinxalchemy: <https://sphinxalchemy.readthedocs.io/>
.. \_GINO: <https://github.com/python-gino/gino> ⭐ 2,794 | 🐛 54 | 🌐 Python | 📅 2022-02-12
.. \_asyncpg: <https://github.com/MagicStack/asyncpg> ⭐ 8,065 | 🐛 299 | 🌐 Python | 📅 2026-02-27

## Documentation

* <https://docs.sqlalchemy.org/en/latest/>
* <https://docs.sqlalchemy.org/en/latest/intro.html>
* <https://docs.sqlalchemy.org/en/latest/core/tutorial.html>
* <https://docs.sqlalchemy.org/en/latest/orm/tutorial.html>
* <https://docs.sqlalchemy.org/en/latest/glossary.html>

## File and Image Attachments

filedepot\_
DEPOT is a framework for easily storing and serving files in web
applications. Depot features simple integration with SQLAlchemy by providing
customized model field types for storing files attached to your ORM
document.

SQLAlchemy-ImageAttach\_
SQLAlchemy-ImageAttach is a SQLAlchemy extension for attaching images
to entity objects.

sqlalchemy-media\_
Based on `SQLAlchemy-ImageAttach` but using JSON type instead of relation,
and SqlAlchemy's mutable facility, Also supports multiple stores per context.

.. \_filedepot: <https://depot.readthedocs.io/>
.. \_SQLAlchemy-ImageAttach: <https://sqlalchemy-imageattach.readthedocs.io/>
.. \_sqlalchemy-media: <https://github.com/pylover/sqlalchemy-media> ⭐ 92 | 🐛 21 | 🌐 Python | 📅 2023-05-25

## Forms and Data Validations

ColanderAlchemy\_
ColanderAlchemy helps you to auto-generate Colander\_ schemas that are based
on SQLAlchemy mapped classes.

Such Colander schemas can be used with libraries like Deform\_ and helps
remove the need for duplication of schema definitions.

Flask-Validator\_
Data validator for Flask and SQL-Alchemy, working at Model component
with events, preventing invalid data in the columns.
The extension works with event listeners from SQLAlchemy.

FormAlchemy\_
FormAlchemy eliminates boilerplate by autogenerating HTML input fields from a
given model. FormAlchemy will try to figure out what kind of HTML code should
be returned by introspecting the model's properties and generate ready-to-use
HTML code that will fit the developer's application.

WTForms-Alchemy\_
WTForms-Alchemy is a WTForms\_ extension toolkit for easier creation of
model based forms.  Strongly influenced by Django ModelForm.

Sprox\_
Sprox provides an easy way to create forms for web content which are:
automatically generated, easy to customize, and validated. Sprox also
has powerful tools to help you display your content the way you want
to with table and record viewers. Sprox provides a way to fill your
widgets, whether they are forms or other content with customizable data.

.. \_Colander: <https://docs.pylonsproject.org/projects/colander/>
.. \_ColanderAlchemy: <https://github.com/stefanofontanelli/ColanderAlchemy> ⭐ 65 | 🐛 18 | 🌐 Python | 📅 2023-07-11
.. \_Deform: <https://docs.pylonsproject.org/projects/deform/>
.. \_Flask-Validator: <https://flask-validator.readthedocs.io/>
.. \_FormAlchemy: <https://github.com/FormAlchemy/formalchemy> ⭐ 81 | 🐛 13 | 🌐 Python | 📅 2020-11-13
.. \_WTForms: <https://wtforms.readthedocs.io/>
.. \_WTForms-Alchemy: <https://wtforms-alchemy.readthedocs.io/>
.. \_Sprox: <https://sprox.org/>

## Full-text Searching

SQLAlchemy-Searchable\_
Full-text searchable models for SQLAlchemy. Only supports PostgreSQL.

.. \_SQLAlchemy-Searchable: <https://sqlalchemy-searchable.readthedocs.io/>

SQLAlchemy-FullText-Search\_
Fulltext search support with MySQL & SQLAlchemy.

.. \_SQLAlchemy-FullText-Search: <https://github.com/mengzhuo/sqlalchemy-fulltext-search> ⭐ 91 | 🐛 4 | 🌐 Python | 📅 2021-07-22

## GIS and Spatial Databases

GeoAlchemy\_
GeoAlchemy provides extensions to SQLAlchemy to work with spatial databases.

The current supported spatial database systems are PostGIS\_, Spatialite\_,
MySQL, Oracle, and MS SQL Server 2008.

`GeoAlchemy 2`\_
GeoAlchemy 2 provides extensions to SQLAlchemy for working with
spatial databases.

GeoAlchemy 2 focuses on PostGIS\_.  PostGIS 1.5 and PostGIS 2 are supported.
Spatialite\_ is also supported, but using GeoAlchemy 2 with Spatialite
requires some specific configuration on the application side.

GeoAlchemy 2 aims to be simpler than its predecessor, GeoAlchemy\_.
Simpler to use, and simpler to maintain.

.. \_GeoAlchemy: <https://geoalchemy.readthedocs.io/>
.. \_GeoAlchemy 2: <https://geoalchemy-2.readthedocs.io/>
.. \_PostGIS: <https://postgis.net/>
.. \_Spatialite: <https://www.gaia-gis.it/gaia-sins/>

## Vector Search

pgvector-python\_
pgvector-python extends sqlalchemy to natively work with pgvectors
similarity queries.

pgai\_
pgai allows to easily create vector embeddings for sqlalchemy models
and takes care of any synchronization effort. Built on top of postgres
and pgvector.

.. \_pgvector-python: <https://github.com/pgvector/pgvector-python> ⭐ 1,513 | 🐛 4 | 🌐 Python | 📅 2026-07-06
.. \_pgai: <https://github.com/timescale/pgai/blob/main/docs/vectorizer/python-integration.md> ⚠️ Archived

## Internationalizations

SQLAlchemy-i18n\_
Internationalization extension for SQLAlchemy models.

* Stores translations in separate tables.
* Reflects translation table structures based on
  parent model table structure.
* Supports forcing of given locale.
* Good performance (uses proxy dicts and other advanced SQLAlchemy
  concepts for performance optimization).

.. \_SQLAlchemy-i18n: <https://sqlalchemy-i18n.readthedocs.io/>

## Profilers

flask\_debugtoolbar\_
Debug toolbar with SQLAlchemy query information for Flask.

pyramid\_debugtoolbar\_
Debug toolbar with SQLAlchemy query information for Pyramid.

SQLTap\_
SQLTap is a library that allows you to profile and introspect the queries
that your application makes using SQLAlchemy.

SQLTap helps you understand:

* how many times a sql query is executed
* how much time your sql queries take
* where your application is issuing sql queries from

nplusone\_
Auto-detect the n+1 queries problem in SQLAlchemy (and other Python ORMs)

nplusone detects unnecessary queries caused by lazy loading and unused eager loading.
Integrates with Flask-SQLAlchemy.

.. \_flask\_debugtoolbar: <https://github.com/flask-debugtoolbar/flask-debugtoolbar>
.. \_pyramid\_debugtoolbar: <https://github.com/Pylons/pyramid_debugtoolbar> ⭐ 96 | 🐛 44 | 🌐 Python | 📅 2026-08-02
.. \_SQLTap: <https://github.com/inconshreveable/sqltap> ⭐ 360 | 🐛 10 | 🌐 Python | 📅 2023-05-31
.. \_nplusone: <https://github.com/jmcarp/nplusone> ⭐ 1,068 | 🐛 24 | 🌐 Python | 📅 2022-11-25

## Query helpers

sqlakeyset\_
This library implements keyset-based paging for SQLAlchemy (both ORM and core).

This library has been tested with PostgreSQL and MariaDB/MySQL.
It should work with other SQLAlchemy-supported databases to provided they support `row(` syntax.

.. \_sqlakeyset: <https://github.com/djrobstep/sqlakeyset> ⭐ 395 | 🐛 3 | 🌐 Python | 📅 2026-04-03

## Recipes

* <https://github.com/sqlalchemy/sqlalchemy/wiki/UsageRecipes> ⭐ 12,088 | 🐛 213 | 🌐 Python | 📅 2026-08-14

## Serialization and deserialization

marshmallow-sqlalchemy\_
SQLAlchemy integration with the marshmallow\_ (de)serialization library.

pydantic\_
Data parsing and validation using Python type hints

sqlalchemy-dict\_
SQLAlchemy extension for interacting models with python dictionary.

.. \_marshmallow: <https://marshmallow.readthedocs.io/>
.. \_marshmallow-sqlalchemy: <https://marshmallow-sqlalchemy.readthedocs.io/>
.. \_pydantic: <https://github.com/samuelcolvin/pydantic> ⭐ 28,549 | 🐛 589 | 🌐 Python | 📅 2026-08-14
.. \_sqlalchemy-dict: <https://github.com/meyt/sqlalchemy-dict> ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2020-03-12

## Testing

charlatan\_
Fixtures management for SQLAlchemy and other systems.

factory\_boy\_
Generate fake data and create random fixtures for testing in SQLAlchemy
and many other Python ORM systems.

mixer\_
Generate fake data and create random fixtures for testing in SQLAlchemy
and many other Python ORM systems.

pytest-mrt\_
pytest plugin that tests whether Alembic migrations are safely reversible.
Runs the actual upgrade/downgrade cycle with real data and does static
analysis on migration files.

.. \_charlatan: <https://github.com/uber/charlatan> ⚠️ Archived
.. \_factory\_boy: <https://github.com/FactoryBoy/factory_boy> ⭐ 3,806 | 🐛 208 | 🌐 Python | 📅 2026-01-01
.. \_mixer: <https://github.com/klen/mixer> ⭐ 955 | 🐛 49 | 🌐 Python | 📅 2024-03-08
.. \_pytest-mrt: <https://github.com/croc100/pytest-mrt> ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2026-08-03

## Thin Abstractions

Dataset\_
Easy-to-use data handling for SQL data stores in Python with support for
implicit table creation, bulk loading, and transaction. Dataset also
includes support for freezing data to CSV and JSON flat files.

rdflib-sqlalchemy\_
RDFLib\_ store using SQLAlchemy dbapi as back-end.

PugSQL\_
Loading and execution of parameterized queries stored in files.

SQLSoup\_
SQLSoup provides a convenient way to map Python objects to
relational database tables, with no declarative code of any kind.
It's built on top of the SQLAlchemy ORM and provides a super-minimalistic
interface to an existing database.

SQLModel\_
SQLModel is a library for interacting with SQL databases from Python code, with Python objects.
It is designed to be intuitive, easy to use, highly compatible, and robust. SQLModel is based
on Python type annotations, and powered by Pydantic and SQLAlchemy.

Zillion\_
Zillion is a free, open data warehousing and dimensional modeling tool that
allows combining and analyzing data from multiple datasources through a
simple API. It writes SQL so you don't have to, and it easily bolts onto
existing database infrastructure via SQLAlchemy.

.. \_Dataset: <https://dataset.readthedocs.io/>
.. \_RDFLib: <https://github.com/RDFLib/rdflib> ⭐ 2,495 | 🐛 363 | 🌐 Python | 📅 2026-08-14
.. \_rdflib-sqlalchemy: <https://github.com/RDFLib/rdflib-sqlalchemy> ⭐ 161 | 🐛 16 | 🌐 Python | 📅 2025-06-07
.. \_PugSQL: <https://pugsql.org/>
.. \_SQLSoup: <https://sqlsoup.readthedocs.io/>
.. \_SQLModel: <https://sqlmodel.tiangolo.com/>
.. \_Zillion: <https://totalhack.github.io/zillion/>

## Vendor-specific Extensions

PostgreSQL
..........

`Flask-SQLAlchemy-PGEvents <https://github.com/shawalli/flask-sqlalchemy-pgevents>`\_
Flask extension that uses SQLAlchemy and
`psycopg2-pgevents <https://github.com/shawalli/psycopg2-pgevents>`\_ to
enable event listeners tied into database-layer triggers.

sqlalchemy-crosstab-postgresql\_
New grammar for SQLAlchemy to make handling the `crosstab()` tablefunc
(i.e. pivot tables) in PostgreSQL easy peasy.

sqlalchemy-postgres-copy\_
Wrapper for using PostgreSQL `COPY` with SQLAlchemy for efficient bulk data
imports and exports.

.. \_sqlalchemy-crosstab-postgresql: <https://github.com/makmanalp/sqlalchemy-crosstab-postgresql> ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2018-02-07
.. \_sqlalchemy-postgres-copy: <https://github.com/jmcarp/sqlalchemy-postgres-copy> ⭐ 59 | 🐛 5 | 🌐 Python | 📅 2020-02-29

## Visualizations

sadisplay\_
Simple package for describing SQLAlchemy schema and display raw database tables by reflecting feature.

sqlalchemy\_schemadisplay\_
This module generates images from SQLAlchemy models.

eralchemy\_
ERAlchemy generates Entity Relation (ER) diagram from databases or from SQLAlchemy models.

paracelsus\_
CLI and Library that generates Mermaid and DOT Diagrams from SQLAlchemy models and injects them into documentation.

.. \_sadisplay: <https://bitbucket.org/estin/sadisplay>
.. \_sqlalchemy\_schemadisplay: <https://github.com/fschulze/sqlalchemy_schemadisplay> ⭐ 148 | 🐛 8 | 🌐 Python | 📅 2025-09-19
.. \_eralchemy: <https://github.com/Alexis-benoist/eralchemy> ⭐ 1,424 | 🐛 11 | 🌐 Python | 📅 2026-05-05
.. \_paracelsus: <https://github.com/tedivm/paracelsus> ⭐ 176 | 🐛 12 | 🌐 Python | 📅 2026-07-20

## Web

Framework Integrations
......................

bottle-sqlalchemy\_
A Bottle\_ plugin to manage SQLAlchemy session to your application.

filteralchemy\_
Declarative query builder that auto-generates filter parameters from
models and parses request parameters using marshmallow-sqlalchemy\_
and webargs\_.

Flask-SQLAlchemy\_
Flask-SQLAlchemy is an extension for Flask\_ that adds support for
SQLAlchemy to your application.

Flask-Admin\_
The admin interface framework for Flask\_.
With scaffolding for SQLAlchemy, MongoEngine, pymongo and Peewee.

pyramid\_sqlalchemy\_
pyramid\_sqlalchemy provides everything needed to use SQLAlchemy in
Pyramid\_ applications.

pyramid\_restler\_
pyramid\_restler is a somewhat-opinionated toolkit for building
RESTful Web services and applications on top of the
Pyramid framework (with SQLAlchemy models).

sacrud\_
SACRUD will solve your problem of CRUD interface for SQLAlchemy,
by providing extension for Pyramid\_ (yet) or use it in pure form.
Unlike classical CRUD interface, pyramid\_sacrud\_ allows override and
flexibly customize interface (that is closer to `django.contrib.admin`).

SQLA-wrapper\_
A light and framework-independent wrapper for SQLAlchemy that makes
it really easy to setup and use.

```
- Doesn't change the SQLAlchemy syntax.
- Can paginate the results of the queries.
- Support for multiple databases at the same time.
```

zope.sqlalchemy\_
The aim of this package is to unify the plethora of existing packages
integrating SQLAlchemy with Zope\_'s transaction management.
As such it seeks only to provide a data manager and makes no attempt
to define a zopeish way to configure engines.

context-async-sqlalchemy\_
Provides a convenient way to work with sessions in asynchronous applications using context.
It handles the lifecycle management of the engine, sessions, and transactions.
The main goal is to provide quick and easy access to a session,
without worrying about opening or closing it when it’s not necessary.

.. \_Bottle: <https://bottlepy.org/>
.. \_bottle-sqlalchemy: <https://github.com/iurisilvio/bottle-sqlalchemy> ⭐ 126 | 🐛 0 | 🌐 Python | 📅 2018-05-18
.. \_filteralchemy: <https://github.com/jmcarp/filteralchemy> ⭐ 72 | 🐛 1 | 🌐 Python | 📅 2019-04-08
.. \_Flask: <https://palletsprojects.com/p/flask/>
.. \_Flask-SQLAlchemy: <https://pythonhosted.org/Flask-SQLAlchemy/>
.. \_Flask-Admin: <https://github.com/flask-admin/flask-admin> ⭐ 6,069 | 🐛 128 | 🌐 Python | 📅 2026-08-09
.. \_Pyramid: <https://trypyramid.com/>
.. \_pyramid\_restler: <https://github.com/wylee/pyramid_restler> ⚠️ Archived
.. \_pyramid\_sacrud: <https://pyramid-sacrud.readthedocs.io/>
.. \_pyramid\_sqlalchemy: <https://pyramid-sqlalchemy.readthedocs.io/>
.. \_sacrud: <https://sacrud.readthedocs.io/>
.. \_SQLA-wrapper: <https://github.com/jpscaletti/sqla-wrapper> ⚠️ Archived
.. \_webargs: <https://github.com/marshmallow-code/webargs> ⭐ 1,408 | 🐛 8 | 🌐 Python | 📅 2026-08-13
.. \_Zope: <https://www.zope.org/>
.. \_zope.sqlalchemy: <https://pypi.org/project/zope.sqlalchemy/>
.. \_context-async-sqlalchemy: <https://github.com/krylosov-aa/context-async-sqlalchemy> ⭐ 61 | 🐛 6 | 🌐 Python | 📅 2026-06-14

Other
.....

paginate\_sqlalchemy\_
This module helps dividing large lists of items into pages.
The user is shown one page at a time and can navigate to other pages.

sandman2\_
Generate a curl-able REST HTTP API with searching and filtering
for all tables in a database and an admin UI with Flask-SQLAlchemy
and HTTP Basic Authentication.

sqlalchemy\_mixins\_
A set of well-tested mixins that brings Active Record, Django-like queries, nested eager load and beauty **repr** to your SQLAlchemy.

.. \_paginate\_sqlalchemy: <https://github.com/Pylons/paginate_sqlalchemy> ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2020-03-23
.. \_sandman2: <https://github.com/jeffknupp/sandman2> ⭐ 2,041 | 🐛 45 | 🌐 Python | 📅 2026-08-10
.. \_sqlalchemy\_mixins: <https://github.com/absent1706/sqlalchemy-mixins> ⭐ 788 | 🐛 28 | 🌐 Python | 📅 2024-09-08

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
