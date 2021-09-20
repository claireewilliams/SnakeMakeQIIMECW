# SnakeMakeQIIMECW


This QIIME2 SnakeMake pipeline has been adapted from: https://github.com/shu251/tagseq-qiime2-snakemake

Any use should cite the tagseq-qiime2-snakemake repo and tutorial in addition to this repository and the snakemake software.


USAGE: 

Configure the script with parameters and a path to your sequences by editing the config.yaml file. 

Install snakemake into a conda environment. See here: for installation instructions. https://snakemake.readthedocs.io/en/stable/getting_started/installation.html

Run the script using the command 
`-s snakefile-import summarize`
first to import and summarize sequences.
Next, use 
`snakemake -s Snakefile-16S-18S-TA` 
to run the remainder of the pipeline after setting quality parameters based on the output of step 1. 
