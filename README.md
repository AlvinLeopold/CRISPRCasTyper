# CasPredict

Detect CRISPR-Cas genes, group them into operons, and predict their subtype 

## Installation
### Requirements
##### Prodigal, hmmer, and some python3 modules
It is advised to use [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://www.anaconda.com/) to manage dependencies.
However, if you have the dependencies in your PATH it will still work.

`conda create -n caspredict python=3.8 prodigal hmmer biopython pandas scipy multiprocess`

### CasPredict
##### Clone git repo
`git clone https://github.com/Russel88/CasPredict.git`

## How to run
##### Activate environment
`conda activate caspredict`

##### Run with a nucleotide fasta as input
`CasPredict.py -i genome.fa -o my_output`

##### Use multiple threads
`CasPredict.py -i genome.fa -o my_output -t 20`

##### Check the different options
`CasPredict.py -h`
