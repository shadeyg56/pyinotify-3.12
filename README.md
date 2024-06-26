# Pyinotify, for Python 3.12+

This fork was created so that `pyinotify` can be used on Python 3.12 and up. 
As of Python 3.12, the [asyncore libary](https://github.com/python/cpython/issues/72719) and a few others were removed.
Since this was really only included in `pynotify` for backwards compability, the `asyncore` functionality has been completely removed, since Python 3 has `asyncio`

* License          : MIT
* Project URL      : [http://github.com/seb-m/pyinotify](http://github.com/seb-m/pyinotify)
* Project Wiki     : [http://github.com/seb-m/pyinotify/wiki](http://github.com/seb-m/pyinotify/wiki)
* API Documentation: [http://seb-m.github.com/pyinotify](http://seb-m.github.com/pyinotify)


## Dependencies

* Linux ≥ 2.6.13
* Python ≥ 2.4 (including Python 3.x)


## Install

### Get the current stable version from PyPI and install it with `pip`

    # To install pip follow http://www.pip-installer.org/en/latest/installing.html
    $ sudo pip install pyinotify

### Or install Pyinotify directly from source

    # Choose your Python interpreter: either python, python2.7, python3.2,..
    # Replacing XXX accordingly, type:
    $ sudo pythonXXX setup.py install


## Watch a directory

Install pyinotify and run this command from a shell:

    $ python -m pyinotify -v /my-dir-to-watch
