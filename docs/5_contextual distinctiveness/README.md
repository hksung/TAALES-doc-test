---
sort: 5
---

## Contextual distinctiveness

### Definition
Contextual distinctiveness refers to how many different psychological, lexical, or semantic contexts a word typically appears in. Words that are more contextually distinct—appearing in fewer, more specific contexts—are often considered more difficult or advanced.

### Methodology
Several approaches are used to capture contextual distinctiveness:
- Variety of responses to a word in free association
- Number of different stimuli that elicit a word in free association
- Probability of co-occurrence with frequent words in a narrow window
- Semantic variability across contextual environments in large corpora

### Corpus used
- EAT (Edinburgh Associative Thesaurus), written
- USF Free Association Norms, written
- BNC (British National Corpus), written & spoken
- TASA (Touchstone Applied Sciences Associates), written

### Register
- Written (EAT, USF, BNC, TASA)  
- Spoken (BNC: Co-occurrence)

### Calculated indices

---

#### Free association response types (EAT)
- **Indices**:
  - EAT_types_AW  
  - EAT_types_CW  
  - EAT_types_FW   

---

#### Free association stimuli elicited (USF)
- **Indices**:
  - USF_AW  
  - USF_CW  
  - USF_FW  

---

#### Co-occurrence probability (McD)
- **Methodology**: Kullback-Leibler divergence (relative entropy)
- **Indices**:
  - McD_CD_AW  
  - McD_CD_CW  
  - McD_CD_FW  

---

#### Semantic distinctiveness (Sem_D)
- **Methodology**: Variability of contexts in which a word appears across 1,000-word text sections; Reversed natural log of mean LSA cosine similarity across chunks
- **Indices**:
  - Sem_D_AW  
  - Sem_D_CW  
  - Sem_D_FW  

---

#### Latent semantic analysis (LSA)
- **Indices**:
	- lsa_average_top_three_cosine
	- lsa_max_similarity_cosine
	- lsa_average_all_cosine

---

### References
- Kiss et al., 1973
- Nelson, McEvoy, & Schreiber, 1998
- McDonald & Shillcock, 2001; Burnage & Dunlop, 1992/3
- Hoffman, Ralph, & Rogers, 2013
- Landauer et al., 2014; Dascalu et al., 2016

---

#### to-do-list
- Find/update all the references on this page. (alphabetical order)