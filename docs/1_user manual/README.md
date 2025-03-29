---
sort: 1
---

## User manual 
- TAALES 2.8 (last updated 1-26-2018)
- This page is adapted from [here](https://www.linguisticanalysistools.org/taales_2_5_beta.html).

## Getting started
1. **Download TAALES**: Get the version appropriate for your operating system.  
2. **Install Java Development Kit (JDK)**: Ensure it matches your OS. *Note*: JDK is required for Hypernymy and Polysemy indices.

## Input
- Files must be plain text (.txt) without markup (e.g., XML, HTML).  
- Files should be located in a single folder.  
- TAALES processes all `.txt` files in the input folder.

## Output
- Output is saved as a `.csv` file, which can be opened with spreadsheet software.  
- Default file name: `results.csv`. Rename the file after each run to avoid overwriting.

## Indices and options
- **Indices**: TAALES 2.8 calculates over 1,000 indices of lexical sophistication across categories.  
- **Norming**: All indices are normed; see the supplementary Index Description Guide for more details.  
- **Part-of-Speech tagging**: Most indices rely on POS tagging and may be less accurate with transcribed spoken texts or non-standard syntactic patterns.  

## Diagnostics
### Index coverage diagnostics
- Indicates the percentage of words in a target text represented in each database.  
- Coverage data is saved in the same folder as the output file with `_index_coverage` appended (e.g., `results_index_coverage.csv`).  
- **Note**: LSA and AOE indices may show lower text coverage due to dimension reduction.

### Individual item diagnostics
- Provides index scores for each item (word, bigram, trigram) and identifies items not included in associated databases.  
- To enable: Check the "Include Individual Item Output?" box under "Select Output Filename".  
- Results are saved in a folder with the same name as the output file, containing tab-delimited text files for each input file.  
- **Note**: AFL, EAT, and USF indices are not supported for individual item diagnostics.

## Citations
Please use the following citations when referencing TAALES:  
- Kyle, K., & Crossley, S. A. (2015). Automatically assessing lexical sophistication: Indices, tools, findings, and application. *TESOL Quarterly, 49*(4), 757–786. https://doi.org/10.1002/tesq.194  
- Kyle, K., Crossley, S. A., & Berger, C. (2018). The Tool for the Analysis of Lexical Sophistication (TAALES): Version 2.0. *Behavior Research Methods, 50*(3), 1030–1046. https://doi.org/10.3758/s13428-017-0926-2

