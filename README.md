jubatus-utils
================================

``jubatus-utils`` is a set of utilities for managing Jubatus.
Currently following tools are available:

* ``jubatop``: monitor Jubatus cluster status in top-like interface
* ``jubamodel``: dump/transform Jubatus 0.5.x model
* ``jubafetch``: online snapshot management of Jubatus model
* ``jubacfg``: jubaconfig wrapper for the rest of us

For the detailed usage, see the built-in documentation using ``--help`` option.

You may also be interested in [Jubash](https://github.com/kmaehashi/jubash), a handy tool that can call Jubatus APIs from command line.

Requirements
----------------

* Jubatus
* Python 2.6 or later
* msgpack-rpc-python package (``pip install msgpack-rpc-python``)

Jubatus Python client is not required.

License
----------------

``jubatus-utils`` is licensed under LGPL 2.1.
