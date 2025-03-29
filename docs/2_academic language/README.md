---
sort: 2
---

## Academic language

### Definition
Academic language contains academic-specific terms and expressions that are less frequent in everyday language use (Kyle et al., 2018). The Academic Word List (AWL) consists of frequently occurring academic words (e.g., *significant*, *analyze*), while the Academic Formulas List (AFL) includes common multi-word expressions found in academic texts (e.g., *in light of*, *in terms of*) (Kim et al., 2018).

### Methodology
TAALES identifies and calculates indices related to academic language using lexical matching techniques against predefined lists (AWL and AFL). Both lists are frequency-based and derived from large academic corpora. Scores are normalized by text length and can include top-proportion (TP) variants.

### Corpus used
- Academic Corpus (for AWL)
- Four Corpora: Simpson et al., 2002; BNC, 2007; Hyland, 2005 (for AFL)

### Calculated indices

#### Academic word list (AWL)

##### AWL general normed scores
- **Definition**: Measures normalized frequency of all words in the AWL.
- **Methodology**: Frequency scores calculated across all AWL word families.
- **Index**: All_AWL_Normed
- **References**: Coxhead, 2000

##### AWL sublist normed scores (Non-TP)
- **Definition**: Measures normalized frequencies for each AWL sublist.
- **Methodology**: Frequencies calculated by sublist and normalized.
- **Indices**: AWL_Sublist_1–10_Normed
- **References**: Coxhead, 2000

##### AWL general normed scores (TP)
- **Definition**: AWL scores based on the top proportion of most frequent AWL words.
- **Methodology**: Normalized scores focusing on high-frequency AWL items.
- **Index**: All_AWL_Normed_TP
- **References**: Coxhead, 2000

##### AWL sublist normed scores (TP)
- **Definition**: Measures sublist-specific AWL frequencies in the top proportion of a text.
- **Methodology**: Calculated within top-proportion segments and normalized.
- **Indices**: AWL_Sublist_1-10_Normed_TP
- **References**: Coxhead, 2000

#### Academic formulaic language (AFL)

##### AFL normed scores
- **Definition**: Measures normalized frequency of formulaic expressions in academic texts.
- **Methodology**: Scores derived from AFL lists across four major academic corpora, categorized by mode (spoken vs. written) and type (core vs. general).
- **Indices**: 
  - All_AFL_Normed
  - Core_AFL_Normed
  - Spoken_AFL_Normed
  - Written_AFL_Normed
- **References**: Simpson-Vlach & Ellis, 2010

---

### References
- Coxhead, A. (2000). A New Academic Word List. *TESOL Quarterly, 34*(2), 213–238.   
- Kyle, K., Crossley, S. A., & Berger, C. (2018). The Tool for the Analysis of Lexical Sophistication (TAALES): Version 2.0. *Behavior Research Methods, 50*(3), 1030–1046.  
- Simpson-Vlach, R., & Ellis, N. C. (2010). An academic formulas list: New methods in phraseology research. *Applied Linguistics, 31*(4), 487–512.
- *Simpson et al., 2002; BNC, 2007, 2007; Hyland, 2005, 2007*

---

#### to-do-list
- Find/update all the references on this page. (alphabetical order)