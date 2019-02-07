Testing
=======

::

    $ brew install libucl
    # This seems like a bad idea at this point
    $ CPPFLAGS="-I$HOME/.homebrew/include" LDFLAGS="-L/Users/jodewey/.homebrew/Cellar/libucl/0.8.1/lib" pip install ucl
    $ virtualenv .venv --no-site-packages
    $ source .venv/bin/activate
    $ pip install -e .
    $ pip install -r requirements-doc.txt
    $ pip install -r requirements-test.txt
    $ pip install -r requirements.txt
    $ pip install tox

    $ tox
