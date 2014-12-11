INTODB
======

DESCRIPTION
-----------

Intodb.pl provides a mechanism for storing benchmark results, processing
them and generating graphs from the data. Data is stored in a SQLite
database and, currently, graphs are generated using the jgraph tool
([[http://www.cs.utk.edu/~plank/plank/jgraph/jgraph.html]]).


USER GUIDE
----------

Type './intodb.pl man' or 'perldoc ./intodb.pl' to see the user guide
(it requires the 'perldoc' command). See the REQUIREMENTS section in
the user guide to see the required perl modules (you may download and
install them from CPAN [[http://www.cpan.org]]).


WARNING
-------

Intodb.pl was conceived as a fast tool to process and store data extracted
from benchmarks (usually in form of csv files) and to provide a flexible
mechanism to generate an approximate graphical representation of such
data. The statistical process to generate the graphical representations
may be inaccurate and cannot be used as a substitute of a proper statistical
analysis: use it at your own risk.


LICENSE
-------

Copyright (C) 2009-2014  Ernest Artiaga

This program comes with ABSOLUTELY NO WARRANTY. This is free software
and you are welcome to redistribute it under certain conditions; see 
the LICENSE file or type './intodb.pl license' for details.


ACKNOLEDGEMENTS
---------------

There have been several contributors to this project who provided
suggestions, bug fixes, and code. My acknowledgment to all of them
(and my apologies if the list is not exhaustive).

* Juanjo Costa
* Jonathan Martí
* Alberto Miranda
* Martin Rehr

