============================
initialize_bodhi_db man page
============================

Synopsis
========

``initialize_bodhi_db`` ``CONFIG_URI``


Description
===========

``initialize_bodhi_db`` is used to create the initial database tables for the Bodhi server. It uses
the given ``CONFIG_URI`` to find the database settings to use.


Example
=======

``$ initialize_bodhi_db /etc/bodhi/production.ini``


Bugs
====

If you find bugs in bodhi (or in the mage page), please feel free to file a bug report or a pull
request::

    https://github.com/fedora-infra/bodhi
