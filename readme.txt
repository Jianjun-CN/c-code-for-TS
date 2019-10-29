
### I got some c++ code for that truncated statistic. 

### tpc is the executable file. It should be executable on cluster. You can type tpc -h to see the help message.

### A sample command is

tpc -p 1000 -i toy_samples.txt -t traitmatrix.txt -n 1 -o p_values.txt

######### the number 1000 behind -p denotes the number of permutation
######### the toy_samples behind -i denotes the input txt, which contains the names of gene, Z statistics, LD matrix.
######### We only consider on trait in our analysis, and thus you can set the traitmatrix.txt behind -t as 1.
######### the value 1 behind -n means that we only consider one trait.
######### the p_value.txt behind -o denotes the output txt, which contains two coloum, one denotes gene name and the other one denotes the final p values.


