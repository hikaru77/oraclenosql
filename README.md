ORACLENOSQL Python API
===========

Python API to access kvstore (Oracle NoSQL).

HOW-TO-INSTALL
-----------------------------------------------


DOWNLOADING DEPENDENCIES
-----------------------------------------------
In order to run this library you will need to
download some python libraries typing the next:

if you don't have pip installing:
- download get-pip.py script from https://bootstrap.pypa.io/get-pip.py
- type: python get-pip.py

Once you have pip installed (you might need sudo access):
- type: pip install multiprocessing pytest

SET THE ENVIRONMENT
----------------------------------------------
In order to have this library working you will need to 
set the following environment variables through the
following commands (from command line):

- export KVSTORE_HOME_DIR="path/to/kvstore/root/dir"
- export KVPROXY_HOME_DIR="path/to/proxy/root/dir"
- export THRIFT_HOME_DIR="path/to/thrift/installation/root/dir"

TO RUN THE TESTCASES
----------------------------------------------
In order to execute the testcases you must go to
oraclenosql/oraclenosql/test directory and type the
following commands depending on what testcase you
want to execute:

- For get testcases: python get.py
- For put testcases: python put.py
- For putIfAbsent testcases: python putIfAbsent.py
- For putIfPresent testcases: python putIfPresent.py
- For putIfVersion testcases: python putIfVersion.py
- For open/close testcases: python open.py
- For connect/close testcases: python connect.py