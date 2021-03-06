jsonrpc-base: a compact JSON-RPC client library interface supporting multiple backends
=======================================================================================================

.. image:: https://travis-ci.org/armills/jsonrpc-base.svg
    :target: https://travis-ci.org/armills/jsonrpc-base
.. image:: https://coveralls.io/repos/armills/jsonrpc-base/badge.svg
    :target: https://coveralls.io/r/armills/jsonrpc-base

This is a compact and simple JSON-RPC client implementation interface python code. This code is forked from https://github.com/gciotta/jsonrpc-requests

Main Features
-------------

* Python 2.7, 3.4, 3.5 & 3.6 compatible
* Supports nested namespaces (eg. `app.users.getUsers()`)
* 100% test coverage

Usage
-----

See `jsonrpc-async <https://github.com/armills/jsonrpc-async>`_ and `jsonrpc-websocket <https://github.com/armills/jsonrpc-websocket>`_ for example implementations.

Tests
-----
Install the Python tox package and run ``tox``, it'll test this package with various versions of Python.

Changelog
---------
1.0.1 (July 6, 2018)
~~~~~~~~~~~~~~
- Falsey values are no longer treated as None for message IDs, or request parameters.

Credits
-------
`@gciotta <https://github.com/gciotta>`_ for creating the base project `jsonrpc-requests <https://github.com/gciotta/jsonrpc-requests>`_.

`@mbroadst <https://github.com/mbroadst>`_ for providing full support for nested method calls, JSON-RPC RFC
compliance and other improvements.

`@vaab <https://github.com/vaab>`_ for providing api and tests improvements, better RFC compliance.
