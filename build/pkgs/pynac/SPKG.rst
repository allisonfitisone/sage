pynac: A fork of the symbolic computation software GiNaC that uses Python objects
=================================================================================

Description
-----------

A modified version of GiNaC that replaces the dependency on CLN by
Python.

License
-------

GPL V2+


Upstream Contact
----------------

-  http://pynac.org
-  Burcin Erocal - burcin spam.erocal.org
-  William Stein - wstein spam.gmail.com
-  Mike Hansen - mhansen spam.gmail.com

Dependencies
------------

Python


Special Update/Build Instructions
---------------------------------

If build fails trying to run autoheader, run

   autoreconf -i --force

in the src directory.
