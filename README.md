# Test-Suites
  Test Suites written in Bash script for error tracking of program outputs
  1. produceOutputs:
    Obtains input from a suite-file to be directed to a program that needs to be tested. The suite-file contains the filename 
    stems for testing. 
    produceOutputs will redirect the output from the program to an available filename.out file.
    Prints errors such as incorrect number of Command Line arguments or missing filename.in or filename.out files to stderr.
    
    Invoked in Command line as:
     ./produceOutputs suite-file program
     
     
  2. runSuite :
    Compares result of a program output with an expected result from a file. 
    runSuite will print the output of the program along with the expected result(stored in filename.out file) if the program 
    has incorrect implementation. 
    Prints errors such as incorrect number of Command Line arguments or missing filename.in or filename.out files to stderr.
    
    Invoked in Command Line as:
    ./runSuite suite-file program
    
