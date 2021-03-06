GitDB
=====

GitDB allows you to access bare git repositories for reading and writing. It 
aims at allowing full access to loose objects as well as packs with performance 
and scalability in mind. It operates exclusively on streams, allowing to operate 
on large objects with a small memory footprint.

REQUIREMENTS
============

* Python Nose - for running the tests

SOURCE
======
The source is available in a git repository at gitorious and github:

git://github.com/gitpython-developers/gitdb.git

Once the clone is complete, please be sure to initialize the submodules using

 cd gitdb
 git submodule update --init

Run the tests with 
 
 nosetests

MAILING LIST
============
http://groups.google.com/group/git-python

ISSUE TRACKER
=============
https://github.com/gitpython-developers/gitdb/issues

LICENSE
=======

New BSD License
