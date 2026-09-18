# Chemical-Exposomebase

### Project Overview

Chemical-Exposomebase is a knowledge base developed to integrate genomic data, environmental toxicant profiles, and population-specific genetic variant information into a unified, queryable resource. The project aims to provide a dynamic platform for investigating the relationships between chemical exposures, genetic variation, and their potential contribution to complex disease susceptibility.

The underlying data are structured within a relational SQLite database, enabling efficient querying and retrieval. An interactive Shiny application layer is built on top of this database to support real-time exploration, filtering, and visualisation of toxin–gene–variant relationships.

**Data Sources**

1. Ensembl 1000 Genomes Project

- Data type: Genomic variant data (VCF format)
- Version: Latest available release (GRCh38; 1000 Genomes Project, Phase 3)
- Description: Provides high-resolution genetic variation data across diverse human populations, including single nucleotide polymorphisms (SNPs), insertions/deletions (indels), and structural variants. This dataset underpins the population genetics and variant-level analyses conducted in this project.
- Source: [Ensembl 1000 Genomes Project](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20130502/)

2. Toxin and Toxin Target Database (T3DB)

- Data type: Chemical and toxicological reference data
- Version: T3DB v2.0
- Description: A curated database of over 3,600 toxic chemicals and their associated biological targets, mechanisms of action, and toxicity profiles. T3DB provides the toxicological foundation linking environmental chemical exposures to genetic targets within this project.
- Source: [T3DB](https://www.t3db.ca/downloads)
