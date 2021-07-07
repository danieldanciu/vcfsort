# vcfsort
Sorts a VCF file (for human) by position

It is assumed that the VCF file is sorted lexicographically by an inane tool such as bcftools, i.e. the order of the chromosomes is [1, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 2, 20, 21, 22, 3, 4, 5, 6, 7, 8, 9, X, Y] and this script wil rearrange the chromosomes to [1-22, X, Y]
