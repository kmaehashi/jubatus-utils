jubatus-utils
================================

``jubatus-utils`` is a set of utilities for managing Jubatus.
Currently following tools are available:

* ``jubafetch``: online snapshot management of Jubatus model
* ``jubatop``: monitor Jubatus cluster status in top-like interface
* ``jubacfg``: jubaconfig for the rest of us
* ``zk``: Wrapper for ZooKeeper Four Letter Commands

For the detailed usage, see the built-in documentation using ``--help`` option.

You may also be interested in [Jubash](https://github.com/kmaehashi/jubash), a handy tool that can call Jubatus APIs from command line.

Requirements
----------------

* Python 2.6 or 2.7 (for jubafetch, jubatop)
  * msgpack-rpc-python package (``pip install msgpack-rpc-python``)
  * Jubatus Python client is *not* required.

Looking for ``jubamodel`` command?
------------------------------------------

As of Jubakit 0.4.0 (released on October 31st, 2016), ``jubamodel`` is now a part of the official distribution of Jubatus!

``jubamodel`` is included in ``jubakit`` package maintained by Jubatus Team.
You can install ``jubakit`` package by:

```
$ pip install jubakit
```

License
----------------

``jubatus-utils`` is licensed under LGPL 2.1.
