# VCF sort (by position, numerical)
Sorts a VCF file (for human) by chromosome

It is assumed that the VCF file is sorted lexicographically by an inane tool such as bcftools, i.e. the order of the chromosomes is [1, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 2, 20, 21, 22, 3, 4, 5, 6, 7, 8, 9, X, Y] and this script wil rearrange the chromosomes to [1-22, X, Y], such that it can be used by tools such as MuTect.

## Usage

```
python sort_vcf.py -i <input_vcf> -o <output_vcf>
```
