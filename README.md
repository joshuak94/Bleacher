# Bleacher
A tool for ChIP-seq normalization.

# Usage
Clone the repository using `git clone git@github.com:joshuak94/Bleacher.git`.
The script can be found in `scripts/wiggletoolsSigNorm.py`.

# Prerequisites
The user must have Wiggletools installed and in their PATH. Installation instructions can be found here: https://github.com/Ensembl/WiggleTools
The user should also have wigToBigWig installed. This can be obtained here: https://www.encodeproject.org/software/wigtobigwig/

# Example usage
`scripts/wiggletoolsSigNorm.py -i input.bam -m mappability.bw -c 1`

# Input
The input files are a ChIP-seq BAM file, a genome mappability file, and a number of cores to use.
