# mqlparser [![Build Status](https://travis-ci.org/pudo/mqlparser.svg?branch=master)](https://travis-ci.org/pudo/mqlparser)

A query parser for the Metaweb Query Language (formerly Freebase, now
Google). The class will accept a query object and provide a parse tree
that can be used to build queries against a variety of backends (e.g.
SQL, SPARQL or another web service).

Specification: [Metaweb Query Language](http://mql.freebaseapps.com/ch03.html).

## Tests

The test suite will usually be executed in it's own ``virtualenv`` and perform a
coverage check as well as the tests. To execute on a system with ``virtualenv``
and ``make`` installed, type:

```bash
$ make test
```
