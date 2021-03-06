.. image:: https://travis-ci.org/agronholm/asyncio_extras.svg?branch=master
  :target: https://travis-ci.org/agronholm/asyncio_extras
  :alt: Build Status
.. image:: https://coveralls.io/repos/agronholm/asyncio_extras/badge.svg?branch=master&service=github
  :target: https://coveralls.io/github/agronholm/asyncio_extras?branch=master
  :alt: Code Coverage

This library provides several conveniences to users of asyncio_:

* decorator for making asynchronous context managers (like ``contextlib.contextmanager``)
* decorator and context manager for running a function or parts of a function in a thread pool
* helpers for calling functions in the event loop from worker threads and vice versa
* helpers for doing non-blocking file i/o


Project links
-------------

* `Documentation`_
* `Source code`_
* `Issue tracker`_

.. _asyncio: https://docs.python.org/3/library/asyncio.html
.. _Documentation: http://pythonhosted.org/asyncio_extras/
.. _Source code: https://github.com/agronholm/asyncio_extras
.. _Issue tracker: https://github.com/agronholm/asyncio_extras/issues
