.. _asyncio:

=================
 asyncio Support
=================

By default, pyfuse3 uses asynchronous I/O using Anyio_ (and most of the
documentation assumes that you are using Anyio). Anyio is compatible with
both asyncio and Trio_, so you can use pyfuse3 from asyncio without
changes.

.. _Trio: https://github.com/python-trio/trio
.. _Anyio: https://github.com/agronholm/anyio
