# Automated-Script-Tester
Lightweight python script to execute .py files and compare actual outputs against expected output using iterative testing. Generates a .csv report file with testing results that includes a boolean comparison of actual output versus expected output along with execution times for each argument fed to the testing program.

To use:

1. Edit Inputs_Outputs.csv with your program arguments and expected outputs
2. Edit execution line 25 in scriptTester.py to point program to your python script name (replacing "numSquared .py")
3. Run program

A sample python script (numSquared.py) is included to maintain program functionality in the absence of a custom script. If the jupyter notebooks file is used, program will also display a line graph plotting inputted program arguments against execution time.
