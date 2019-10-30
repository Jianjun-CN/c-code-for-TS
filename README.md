# Test based on Truncated Statistic. 

tpc is the pre-compiled executable binary for Linux.

### Current Version
* v1.0

### The quick start commands are

`tpc -h` to get the more help information.

`tpc -p 1000 -i toy_samples.txt -t traitmatrix.txt -n 1 -o p_values.txt`

The number 1000 behind `-p` denotes the number of permutation.

The `toy_samples.txt` behind `-i` denotes the input txt, which contains the names of gene, Z statistics, LD matrix.

We only consider one trait in our analysis, and thus you can put 1 into the `traitmatrix.txt` that is behind `-t`

The value 1 behind `-n` means that we only consider one trait.

The `p_value.txt` behind `-o` denotes the output txt, which contains two columns, i.e., gene names and final p-values.
