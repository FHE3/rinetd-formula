======
rinetd
======

Manage ``rinetd``

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``rinetd``
----------

Includes

* ``rinetd.install``
* ``rinetd.config``

``rinetd.install``
------------------

Installs the package and manages the service.

``rinetd.config``
-----------------

Configures ``rinetd`` and restarts the service (if necessary).

``rinetd.remove``
-----------------

* Stops the service.
* Removes the package.
* Deletes the config.

TODO
====

* Handle logging.
