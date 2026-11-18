# Erwinia Genome Assembly and Comparative Genomics

**UC Berkeley coursework | Computational genomics | 2025**

This project documents my individual contributions to a collaborative KBase analysis of an *Erwinia* isolate. I focused on sequencing-read quality control, comparing bacterial genome assembly strategies, exploring genome annotations, and building exploratory phylogenetic trees. The broader group project examined whether the isolate resembled plant-pathogenic or environmentally adapted/epiphytic *Erwinia* species.

## My contributions

### Sequencing data quality control
- Examined Illumina paired-end read quality using **FastQC**, including sequence-content and adapter-content warnings.
- Applied **Trimmomatic** to Illumina reads and **Filtlong** to Oxford Nanopore long reads to compare filtered and unfiltered assembly inputs.

### Genome assembly comparison
- Compared **Flye**, **SPAdes**, and **Unicycler** assemblies using short-read, long-read, and hybrid strategies.
- Evaluated contig counts, contig lengths, **N50/L50**, GC content, and predicted gene counts to interpret differences among assemblies.
- In the documented comparisons, the Flye assembly of raw Nanopore reads produced three circular contigs, with the longest contig measuring **4,459,326 bp** and **4,265 predicted genes**. These metrics were interpreted in the context of the other assemblies rather than treated as independent validation of completeness.

### Annotation and evolutionary analysis
- Explored annotated features and selected housekeeping genes including **gyrB, rpoB, atpD, infB, and recA**.
- Used **MUSCLE** for multiple sequence alignment and **FastTree2** for exploratory gene-tree reconstruction across *Erwinia* species.
- Compared gene-level relationships with the group's broader species-tree analysis and documented limitations of the gene-tree approach.

## Tools

KBase · FastQC · Trimmomatic · Filtlong · Flye · SPAdes · Unicycler · MUSCLE · FastTree2

## Scope and attribution

This README summarizes **my work within a group coursework project**, not the entire team's contributions. The original KBase Narrative includes run details, results, and reflections. It is not included here because only a text export of my contributions was supplied; the underlying sequencing datasets, reports, and executable workflow files are not part of this repository.

**Relevant skills:** NGS data quality assessment, short- and long-read sequencing analysis, assembly benchmarking, genome annotation exploration, and technical documentation.
