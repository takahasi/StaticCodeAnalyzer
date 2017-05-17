# StaticCodeAnalyzer

Build status
------------
[![Build Status](https://travis-ci.org/takahasi/StaticCodeAnalyzer.svg?branch=master)](https://travis-ci.org/takahasi/StaticCodeAnalyz)

Usage
-----
./analyze.sh {option}

Description
-----------
This is script for several static analysis.

Environment
-----------
* WORK SPACE        = . (deault)
* SOURCE DIRECTORY  = ./src (default)
* RESULTS DIRECTORY = ./result_yyyymmdd (default)

Options
-------

Option | Note
------ | ----
-h,--help | Print usage
--cppcheck | analyze with cppcheck
--cccc | analyze with cccc
--sloccount | analyze with sloccount
--cpd |  analyze with cpd
--cpplint | analyze with cpplint
--all|  analyze with all methods

Examples
--------
* Executes all analysis
** `$ ./analyze.sh --all`
* Executes CPD & CPPCHECK
** `$ ./analyze.sh --cpd --cppcheck`
* Show help message
** `$ ./analyze.sh --help`
