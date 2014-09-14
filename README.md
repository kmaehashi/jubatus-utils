jubatus-utils
================================

``jubatus-utils`` is a set of utilities for managing Jubatus.
Currently following tools are available:

* ``jubamodel``: dump/transform Jubatus model
* ``jubafetch``: online snapshot management of Jubatus model
* ``jubatop``: monitor Jubatus cluster status in top-like interface
* ``jubacfg``: jubaconfig for the rest of us
* ``zk``: Wrapper for ZooKeeper Four Letter Commands

For the detailed usage, see the built-in documentation using ``--help`` option.

You may also be interested in [Jubash](https://github.com/kmaehashi/jubash), a handy tool that can call Jubatus APIs from command line.

Requirements
----------------

* Jubatus
  * ``jubamodel`` requires Jubatus 0.5 or later
* Python 2.6 or later
* msgpack-rpc-python package (``pip install msgpack-rpc-python``)

Jubatus Python client is not required.

License
----------------

``jubatus-utils`` is licensed under LGPL 2.1.
