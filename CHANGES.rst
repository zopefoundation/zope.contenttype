================
 Change History
================

4.3.0 (2017-08-10)
==================

- Add support for Python 3.6.

- Drop support for Python 3.3.

- Host documentation at https://zopecontenttype.readthedocs.io


4.2.0 (2016-08-26)
==================

- Add support for Python 3.5.

- Drop support for Python 2.6.

4.1.0 (2014-12-26)
==================

- Add support for Python 3.4 and PyPy3.

- Add support for testing on Travis.

4.0.1 (2013-02-20)
==================

- Change the file contents argument of ``guess_content_type`` from string
  to bytes.  This change has no effect on Python 2.

4.0.0 (2013-02-11)
==================

- Add some tests for better coverage.

- Add ``tox.ini`` and manifest.

- Add support for Python 3.3 and PyPy.

- Drop support for Python 2.4 and 2.5.

3.5.5 (2011-07-27)
==================

- Properly restore the HTML snippet detection, by looking at the entire string
  and not just its start.

3.5.4 (2011-07-26)
==================

- Restore detection of HTML snippets from 3.4 series.

3.5.3 (2011-03-18)
==================

- Add new mime types for web fonts, cache manifest and new media formats.

3.5.2 (2011-02-11)
==================

- LP #717289:  add ``video/x-m4v`` mimetype for the ``.m4v`` extension.

3.5.1 (2010-03-23)
==================

- LP #242321:  fix IndexError raised when testing strings consisting
  solely of leading whitespace.

3.5.0 (2009-10-22)
==================

- Move the implementation of ``zope.publisher.contenttype`` to
  ``zope.contenttype.parse``, moved tests along.

3.4.3 (2009-12-28)
==================

- Update mime-type for ``.js`` to be application/javascript.

3.4.2 (2009-05-28)
==================

- Add MS Office 12 types based on:
  http://www.therightstuff.de/2006/12/16/Office+2007+File+Icons+For+Windows+SharePoint+Services+20+And+SharePoint+Portal+Server+2003.aspx

3.4.1 (2009-02-04)
==================

- Improve ``text_type()``. Based on the patch from
  http://www.zope.org/Collectors/Zope/2355/

- Add missing ``setuptools`` dependency to setup.py.

- Add reference documentation.

3.4.0 (2007-09-13)
==================

- First stable release as an independent package.
