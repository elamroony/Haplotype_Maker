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


**Output file:**
