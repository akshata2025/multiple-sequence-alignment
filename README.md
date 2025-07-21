# Cytochrome C Phylogenetic Analysis

This project performs **Multiple Sequence Alignment (MSA)** and **Phylogenetic Tree Construction** of **Cytochrome C proteins** from five different species.

## Files Included

| File | Description |
|------|-------------|
| `cytochrome_c.fasta` | Input protein sequences in FASTA format |
| `alignment_named.aln` | Multiple Sequence Alignment output (Clustal format) |
| `cytochrome_distance_matrix.csv` | Pairwise distance matrix (BLOSUM62) |
| `cytochrome_c_tree.newick` | Phylogenetic tree in Newick format |
| `cytochrome_c_tree.png` | Visualized phylogenetic tree (PNG image) |
| `msa_phylogenetree.ipynb` | Full analysis pipeline (Google Colab/Jupyter Notebook) |

---

## Workflow Overview

**Input Sequences**  
Cytochrome C protein sequences from:  
- *Drosophila melanogaster*  
- *Homo sapiens*  
- *Escherichia coli*  
- *Mus musculus*  
- *Equus caballus*


**Multiple Sequence Alignment**  
Performed using Clustal Omega via Biopython , EBI API.

**Distance Matrix**  
Calculated using the BLOSUM62 substitution matrix.

**Phylogenetic Tree Construction**  
Tree built using the Neighbor-Joining method.

**Visualization**  
Tree visualized with Matplotlib + Biopython.

##Project by [Akshata P Pauskar]


### Run in Google Colab:

Click the badge below to open and run the notebook in Colab directly:

[![Open In Colab](https://colab.research.google.com/github/akshata2025/multiple-sequence-alignment/blob/main/msa_phylogenetree.ipynb)

---

## License

This project is open-source and free to use under the MIT License.
