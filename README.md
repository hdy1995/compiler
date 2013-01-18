Compiler
========

##Description
A compiler for a made-up language.

##Author
Created by [Evan Sneath](http://github.com/evansneath).

##License
This software licensed under the [Open Software License v3.0](http://www.opensource.org/licenses/OSL-3.0).

##Dependencies
In order to run, this software requires the following dependencies:

* [Python 3.3](http://python.org/download/releases/3.3.0/)

##Progress

<table>
<tr><td><b>Component</b></td><td><b>Status</b></td></tr>
<tr><td>Scanning</td><td>Completed</td></tr>
<tr><td>Parsing</td><td>Not Started</td></tr>
<tr><td>Type Checking</td><td>Not Started</td></tr>
<tr><td>Code Generation</td><td>Not Started</td></tr>
<tr><td>Runtime</td><td>Not Started</td></tr>
</table>

##Usage
To start the compiler, run:
```
./compiler.py <source> <target>
```
Where `<source>` is the source file to compiler and `<target>` is the destination
file for the intermediate code.
<br/><br/>
At the moment, the compiler will scan the source file for all valid tokens
and any warnings or errors that may arrise. All valid tokens are printed as
they are encountered.
<br/><br/>
The `test` directory contains a test source file which has several examples of
token parsing and error/warning handling.
