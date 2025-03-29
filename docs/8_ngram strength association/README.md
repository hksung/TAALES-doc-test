---
sort: 8
---

## Ngram strength of association

### Definition
Ngram strength of association (SOA) measures how strongly the words in an ngram are connected based on their co-occurrence patterns. These indices are especially useful for analyzing collocations, idiomatic expressions, and lexical cohesion within texts (Gablasova et al., 2017; O'Donnell et al., 2013).

### Methodology
TAALES calculates five statistical association measures for bigrams and trigrams across COCA subcorpora:
- **MI**: Mutual Information
- **MI²**: Mutual Information Squared
- **T**: T-score
- **DP**: Delta P (predictive association)
- **AC**: Approximate Collexeme (semantic co-occurrence)

### Corpus Used
- COCA

### Register
- Academic, Fiction, Magazine, News, Spoken

### Calculated Indices
- Replace `[ ]` with register (e.g., *academic*, *fiction*): e.g., 
COCA_academic_bi_MI, COCA_fiction_bi_MI.

#### Mutual Information (MI)

- **Description**: Highlights rare but highly exclusive combinations. Sensitive to low-frequency ngrams.
- **Indices**:
  - COCA_[ ]_bi_MI  
  - COCA_[ ]_tri_MI  
  - COCA_[ ]_tri_2_MI  

#### Mutual Information Squared (MI²)

- **Description**: Modifies MI to reduce low-frequency bias by squaring the numerator. Favors exclusive, yet not extremely rare, combinations.
- **Indices**:
  - COCA_[ ]_bi_MI2  
  - COCA_[ ]_tri_MI2  
  - COCA_[ ]_tri_2_MI2  

#### T Score (T)

- **Description**: Emphasizes more frequent word combinations with weaker associations. Often reflects formulaic or generic phrases.
- **Indices**:
  - COCA_[ ]_bi_T  
  - COCA_[ ]_tri_T  
  - COCA_[ ]_tri_2_T  

#### Delta P (DP)

- **Description**: Captures predictive strength in directional co-occurrence. A high DP score means one word strongly predicts the next.
- **Indices**:
  - COCA_[ ]_bi_DP  
  - COCA_[ ]_tri_DP  
  - COCA_[ ]_tri_2_DP  


#### Approximate Collexeme (AC)

- **Description**: Measures how semantically cohesive a word pair is. High AC scores indicate formulaic or strongly related word sequences.
- **Indices**:
  - COCA_[ ]_bi_AC  
  - COCA_[ ]_tri_AC  
  - COCA_[ ]_tri_2_AC  

---

### Notes
- ...

---

### References
- Davis..

---

#### to-do-list
- Find/update all the references on this page. (alphabetical order)
- add what is the difference between COCA_fiction_tri_MI, COCA_fiction_tri_2_MI in the note section.
