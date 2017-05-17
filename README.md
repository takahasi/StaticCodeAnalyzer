# StaticCodeAnalyzer

Build status
------------
[![Build Status](https://travis-ci.org/takahasi/StaticCodeAnalyzer.svg?branch=master)](https://travis-ci.org/takahasi/StaticCodeAnalyz)

Usage
-----
  ./analyze.sh

Description
-----------
  This is script for several static analysis.

Environment
-----------
  WORK SPACE        = . (deault)
  SOURCE DIRECTORY  = ./src (default)
  RESULTS DIRECTORY = ./result_yyyymmdd (default)

Options
-------
  -h,--help       : Print usage
  --cppcheck      : analyze with cppcheck
  --cccc          : analyze with cccc
  --sloccount     : analyze with sloccount
  --cpd           : analyze with cpd
  --cpplint       : analyze with cpplint
  --all           : analyze with all methods

Examples
--------
* Executes all analysis;
  `\$ $0 --all`
* Executes CPD & CPPCHECK;
  `\$ $0 --cpd --cppcheck`
* Show help message;
  `\$ $0 --help`

