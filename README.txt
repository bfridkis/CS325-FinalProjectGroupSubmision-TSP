README.TXT - CS325 FINAL PROJECT - TRAVELING SALESMAN PROBLEM

To execute Group65TSP, perform the following steps:
1.  Copy source files (QuadTree.cpp, QuadTree.h, RunTSP.cpp & Makefile) to the directory of your choice.

2.  Navigate to this directory (i.e. the directory to which the files were pasted in step 1) 
	in your system's terminal/console.
	
3.  Place a test file (with a name of your choosing) in this same directory.
	(This test file contains city numbers, city x-coordiantes, and city y-coordinates space seperated, with one
	 city represented per line.)
	
3.  Type the command "make" (without quotes).
	This will compile the program (Group65TSP).
	
4.  Type the command "./Group65TSP" (without quotes) followed by the name of the test file. 
		-For example, if test file is named "tsp_example_1.txt", type "./Group65TSP tsp_example_1.txt" 
		 in the command line (without quotes).
	This will execute the program (Group65TSP) with the specified test file.

6.  The results will be output to a file named as the concatenation of test file name + .tour
		-For example, if the test file is named "tsp_example_1.txt", the results output
		 file will be named "tsp_example_1.txt.tour", located in the same directory from
		 which the program is run.  
	
5.  Once finished with program, type the command "make clean" (without quotes)
    to delete the object files and the executable file generated in the steps above.
    (Ignore any "rm: cannot remove..." errors.)