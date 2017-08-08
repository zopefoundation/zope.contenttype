=====
 API
=====

There are two major features provided by this package: determining
content types, and parsing text representations of content types into
structured data.

.. currentmodule:: zope.contenttype

.. note:: When this module is imported, it uses :func:`add_files` to
   extend the standard :mod:`mimetypes` database with a set of common
   office and multimedia types and filename extensions.

.. tip:: When used as the main module (e.g., ``python -m
		 zope.contenttype``) this module will print out the
		 :mod:`mimetypes` database.

Determining Content Types
=========================

.. autofunction:: guess_content_type
.. autofunction:: text_type

Utility Functions
-----------------

.. autofunction:: add_files

Parsing Text Representations
============================

.. automodule:: zope.contenttype.parse
