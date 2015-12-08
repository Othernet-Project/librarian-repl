==============
librarian-repl
==============

A helper tool that spawns a python repl, allowing it's user to poke into the
environment used by the running librarian_ process.

Installation
------------

The component has the following dependencies:

- librarian-core_

To enable this component, add it to the list of components in librarian_'s
`config.ini` file, e.g.::

    [app]
    +components =
        librarian_repl

Usage
-----

Start librarian by passing the ``--repl`` flag to it. Example::

    python -m librarian.app --repl

.. _librarian: https://github.com/Outernet-Project/librarian
.. _librarian-core: https://github.com/Outernet-Project/librarian-core
