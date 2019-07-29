
I got some c++ code for that truncated statistic. 

tpc is the program. It should be executable on cluster. You can type tpc -h to see the help message.

A sample command is

tpc -p 1000 -i toy_samples.txt -t traitmatrix.txt -n 3 -o p_values.txt

