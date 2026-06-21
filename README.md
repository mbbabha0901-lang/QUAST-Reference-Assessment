# QUAST-Reference-Assessment

## Overview
This repository contains the results of genome assembly quality assessment performed using **QUAST** with a reference genome.

## Tool Used
- QUAST

## Input Files
- Assembly file (`contigs.fasta`)
- Reference genome (`reference.fasta`)

## Analysis Performed
QUAST was used to compare the assembled contigs against a reference genome and assess assembly quality.

## Output Files
- `report.html`
- `report.pdf`
- `report.tsv`
- `report.txt`
- `basic_stats/`
- `icarus.html`
- `icarus_viewers/`
- `quast.log`
- `transposed_report.tsv`

## Key Metrics
- Number of contigs
- Total assembly length
- GC content
- N50
- L50
- Genome fraction
- Duplication ratio

## Repository Structure

```text
QUAST-Reference-Assessment/
├── basic_stats/
├── icarus_viewers/
├── icarus.html
├── quast.log
├── report.html
├── report.pdf
├── report.tex
├── report.tsv
├── report.txt
├── transposed_report.tex
├── transposed_report.tsv
└── transposed_report.txt
```

## Author
**Abha**

M.Sc. Bioinformatics  
Graphic Era (Deemed to be) University
