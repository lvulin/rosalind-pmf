# Rosalind

This repository contains Python solutions to algorithmic and bioinformatics problems from the [Rosalind](https://rosalind.info/problems/list-view/?location=bioinformatics-textbook-track) platform.

The problems were originally completed as part of university coursework in bioinformatics and focus on applying computational methods to biological sequence data.

## Structure
The repository is organized by chapters (C1–C6), following the Bioinformatics Textbook Track on Rosalind:

- **C1** – Basic string and pattern matching problems  
- **C2** – Motif finding and probabilistic approaches  
- **C3** – Graph-based genome assembly problems  
- **C4** – Peptide and protein-related problems  
- **C5** – Dynamic programming algorithms  
- **C6** – Genome rearrangements 


## Notes

These solutions were revisited and slightly refactored to improve readability, naming, and structure.
The goal of this repository is to demonstrate problem-solving skills, algorithmic thinking, and practical use of Python for computational biology tasks.

## Highlighted problems

Some selected problems from this repository:

#### BA6A – Greedy sorting of signed permutations
Implemented the Greedy Sorting algorithm in Python to transform a signed permutation into the identity permutation through reversal and sign-flip operations, while storing intermediate steps.

#### BA3D / BA3E – De Bruijn graph construction
These tasks implement de Bruijn graph construction in Python, a core concept in genome assembly.
For BA3D, the graph is built from a single input string by generating all k-mers and connecting each k-1 prefix to its k-1 suffix. For BA3E, the graph is built directly from a given collection of k-mers using the same prefix–suffix relationship.
These solutions demonstrate string slicing, dictionary-based graph representation, adjacency list construction, and algorithmic modeling of sequence assembly problems.

#### BA2E – Motif search in DNA sequences
#### BA5E – Sequence alignment using dynamic programming
