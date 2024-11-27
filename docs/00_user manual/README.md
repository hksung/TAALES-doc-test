
## User Manual for TAALES 2.8 (updated 1-26-2018)


### Citations
Please use the following citations when referencing TAALES:  
- Kyle, K. & Crossley, S. A. (2015). Automatically assessing lexical sophistication: Indices, tools, findings, and application. *TESOL Quarterly, 49*(4), pp. 757-786. doi: [10.1002/tesq.194](https://doi.org/10.1002/tesq.194)  
- Kyle, K., Crossley, S. A., & Berger, C. (2018). The tool for the analysis of lexical sophistication (TAALES): Version 2.0. *Behavior Research Methods.*

---

## Getting Started
1. **Download TAALES**: Get the version appropriate for your operating system.  
2. **Install Java Development Kit (JDK)**: Ensure it matches your OS. *Note*: JDK is required for Hypernymy and Polysemy indices.

---

## Indices and Options
- **Indices**: TAALES 2.8 calculates over 1,000 indices of lexical sophistication across categories.  
- **Norming**: All indices are normed; see the supplementary Index Description Guide for more details.  
- **Part-of-Speech Tagging**: Most indices rely on POS tagging and may be less accurate with transcribed spoken texts or non-standard syntactic patterns.  

### Updates in TAALES 2.8
- Improved definitions of **content words** and **function words**:  
  - Content words include nouns, adjectives, most verbs (*excluding "to be"*), and adverbs derived from adjectives.  
  - Function words include all other words.  

### Index Categories
Refer to the Index Description Spreadsheet for details. Included categories:
- **Academic Language**:
  - Academic Formulas List (AFL), Academic Word List (AWL), AWL Sublists
- **COCA Indices**:
  - Word Frequency and Range  
  - Bigram and Trigram Frequency, Range, and Association Strength  
- **Frequency and Range Indices**:
  - BNC, SUBTLEXus, TOEFL 11 corpus, etc.  
- **Other Index Types**:
  - Age of Exposure (AOE), Contextual Distinctiveness, Psycholinguistic Word Information Norms, Hypernymy and Polysemy.

---

## Input
- Files must be plain text (.txt) without markup (e.g., XML, HTML).  
- Files should be located in a single folder.  
- TAALES processes all `.txt` files in the input folder.

---

## Saving Your Output
- Output is saved as a `.csv` file, which can be opened with spreadsheet software.  
- Default file name: `results.csv`. Rename the file after each run to avoid overwriting.

---

## Diagnostics
### Index Coverage Diagnostics
- Indicates the percentage of words in a target text represented in each database.  
- Coverage data is saved in the same folder as the output file with `_index_coverage` appended (e.g., `results_index_coverage.csv`).  
- **Note**: LSA and AOE indices may show lower text coverage due to dimension reduction.

### Individual Item Diagnostics
- Provides index scores for each item (word, bigram, trigram) and identifies items not included in associated databases.  
- To enable: Check the "Include Individual Item Output?" box under "Select Output Filename".  
- Results are saved in a folder with the same name as the output file, containing tab-delimited text files for each input file.  
- **Note**: AFL, EAT, and USF indices are not supported for individual item diagnostics.

