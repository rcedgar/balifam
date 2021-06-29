# balifam
Protein multiple sequence alignment benchmark.

There are three benchmarks: `balifam100`, `balifam1000` and `balifam10000`.

These are Balibase v3 reference alignments with PFAM homologs added.

Directory structure under each benchmark is:

`in/`   
Input sequences.

`ref/`   
Reference alignments. Upper-case regions indicate conservative 
regions that are intended for use in assessment. Lower-case regions 
should not be used.

`info/`   
Contains one file, `ids.txt`, which is a list of set identifiers used as filenames in `ref/` and `in/`.

Accuracy of alignments made by an algorithm can be asssessed by `qscore` (https://github.com/rcedgar/qscore).

# Reference
R.C. Edgar (2021), MUSCLE v5 enables improved estimates of phylogenetic tree confidence by ensemble boostrapping, biorxiv.
