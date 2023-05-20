# Mini-c-code-to-3-address-ir-code
To install lex in linux type:
sudo apt-get install flex

To install yacc in linux type:
sudo apt-get install bison

To generate a three address code fire the command ..build.sh on terminal in 
linux.

OR 

To run different test files write the following commands one by one in linux terminal:
lex program.l
yacc program.y
gcc y.tab.c -ll
./a.out test1

The different test files are:
test1
test2

The output that is the three address code will be found in the output file in the folder after all the commands havebeen executed. To see the three address code open the output file.


