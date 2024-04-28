# Haplotype_Maker
One might be interested in constructing haplotypes based on a particular set of markers (a window) for all samples. HapMaker, a Python code, can be used for this task.    

**Input file:**
The input file contains animal IDs in first column followed by genotypes, which should be phased and the format is 0, 2, 3 and 4. Here is an example for 4 animals and 10 markers:

```
Ani0001 42204023222
Ani0002 04334322334
Ani0003 43340000342
Ani0004 20422433240
```

These genotyped are corresponding to: 
```
Genotype    Allelic format    Haplotype coding
0           AA                11
3           AB                12
4           BA                21
2           BB                22
```


**Output file:** It has 5 columns:

1. Index, from 1 to n, where n is the number of animals.     
2. Animal ID.     
3. Genotypes in the window.      
4. First haplotype.   
5. Second haplotype.   
```
1 Ani0001 0402 1212 1112
2 Ani0002 3432 1212 2122
3 Ani0003 4000 2111 1111
4 Ani0004 2243 2221 2212
```
