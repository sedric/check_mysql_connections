check_mysql_connections
=======================

Checks the number of connections to a mysql server.

 - requires mysqladmin.
 - requires bash.
 - requires utils.sh from nagios plugins package

Original from http://exchange.nagios.org/directory/Plugins/Databases/MySQL/check_mysql_connections/details

Forked because it doesn't seems to be maintained anymore and is broken (tested on MariaDB 10).

Usage
-----

::

   check_mysql_connections.sh [-H hostname] [-P port] [-u username] [-p password] -w <WARNING PERCENT> -c <CRITICAL PERCENT>
