# test
test


```shell
#! /bin/bash

for i in $(ls)
do
   echo $i
don
```

The total memory used during the sorting is around one and a half the size of the SAM file.
For example, to sort a 1.3TB SAM file (such as the [NA24631](ftp://user:anonymous@ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/data/ChineseTrio/HG005_NA24631_son/HG005_NA24631_son_HiSeq_300x/NHGRI_Illumina300X_Chinesetrio_novoalign_bams/) from [GIAB](https://github.com/genome-in-a-bottle/about_GIAB) which is a 300X Whole Genome (2x150-base) paired reads that we aligned with [mpiBWA](https://github.com/bioinfo-pf-curie/mpiBWA)), 1.7 TB of memory are required and splitted over 512 MPI workers (i.e. cores) that corresponds to makes 3.3 Gb of memory per core.

 [toto](ftp://user:pass@111.11.11.111/mydata)
