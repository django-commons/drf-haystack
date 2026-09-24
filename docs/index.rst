==================================
Haystack for Django REST Framework
==================================

Contents:

.. toctree::
   :maxdepth: 2

   01_intro
   02_autocomplete
   03_geospatial
   04_highlighting
   05_more_like_this
   06_term_boost
   07_faceting
   08_permissions
   09_multiple_indexes
   10_tips_n_tricks
   apidoc/modules

About
=====
Small library aiming to simplify using Haystack with Django REST Framework

Features
========

Supported Python and Django versions:

    - Python >=3.11, <3.15
    - `All supported versions of Django <https://www.djangoproject.com/download/#supported-versions>`_


Installation
============
It's in the cheese shop!

.. code-block:: none

    $ pip install drf-haystack


Requirements
============
    - A Supported Django install
    - Django REST Framework v3.16 and later
    - Haystack v3.3.0 and later, below v4
    - A supported search engine such as Solr, Elasticsearch, Whoosh, etc.
    - Python bindings for the chosen backend (see below).
    - (geopy and libgeos if you want to use geo spatial filtering)

Python bindings
---------------

You will also need to install python bindings for the search engine you'll use.

Elasticsearch
.............

See haystack `Elasticsearch <https://django-haystack.readthedocs.io/en/v3.3.0/installing_search_engines.html#elasticsearch>`_
docs for details

.. code-block:: none

    $ pip install elasticsearch>=7.0.0,<8.0.0   # For Elasticsearch 7.x

Solr
....

See haystack `Solr <https://django-haystack.readthedocs.io/en/v3.3.0/installing_search_engines.html#solr>`_
docs for details.

.. code-block:: none

    $ pip install pysolr

Whoosh
......

See haystack `Whoosh <https://django-haystack.readthedocs.io/en/v3.3.0/installing_search_engines.html#whoosh>`_
docs for details.

.. code-block:: none

    $ pip install whoosh

Xapian
......

See haystack `Xapian <https://django-haystack.readthedocs.io/en/v3.3.0/installing_search_engines.html#xapian>`_
docs for details.


Contributors
============

This library has mainly been written by `me <https://github.com/rhblind>`_ while working
at `Inonit <https://github.com/inonit>`_. I have also had some help from these amazing people!
Thanks guys!

    - See the full list of `contributors <https://github.com/django-commons/drf-haystack/graphs/contributors>`_.

Changelog
=========

See `CHANGELOG.md <https://github.com/django-commons/drf-haystack/blob/main/CHANGELOG.md>`_.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
