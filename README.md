parsertest
==========

Unit tests for ECE244 Lab 2.

The bash script 'ptest' uses the input file to test your Parser program.
It will produce an 'output' file which will be compared against the 'solution' file for failures.

To download the script and unit tests, check the releases.
To get it as a zip file from the terminal, use:

wget https://github.com/ECE1T6/parsertest/archive/v1.0.zip
unzip v1.0

Make sure that Parser.cpp is in the same directory as the ptest script as well as the input and solution files.
To run the automated tests:
./ptest

Then any failed unit tests will be outputted to the console.

Everything is opensource, and anyone is free to contribute. If you can think of other corner-case unit tests
that are not covered by the input, please add them to the input file along with the correct output to the solution file.


