Simple online editor for reStructuredText on Flask.

This version has a small change to support Python 3.

The original version can be used online at: http://rst.ninjs.org/

Getting setup
-------------

Requirements for rsted:

* flup-py3
* Flask
* Redis
* rst2html (from Docutils)

These requirements are expressed in the requirements.txt file and may be
installed by running the following (from within a virtual environment)::

    pip install -r requirements.txt


How to run
----------

From within your environment, just run::

    ./application.py

This will start a server on port 5000.  Just visit http://localhost:5000/ in
your browser.
