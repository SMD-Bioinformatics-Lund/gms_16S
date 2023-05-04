# gms-emu.
A taxonomic profiler optimized for long 16S rRNA reads.
https://gitlab.com/treangenlab/emu
Under construction.


#### Quick start
1. Add you samples to a sample_sheet.csv
2. gunzip the files in the database directory (if they are gzipped).
3. Run
``` 
nextflow run main.nf --input assets/samplesheet_mod.csv \
    --outdir results_emu \
    --db /path/to/assets/databases/emu_database \
    --seqtype map-ont \
    -profile singularity,test 
```
