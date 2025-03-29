---
sort: 13
---

## Word Range

### Definition
Word range refers to the number of texts in a corpus in which a particular word occurs. While word frequency is closely linked to language proficiency, it can be inflated by technical terms concentrated in a few documents. Word range helps mitigate this inflation and more accurately represents an individual's likely exposure to specific words.  
Words with more limited range are generally considered more sophisticated.

### Methodology
Word range is calculated as the number of documents or categories in which a word appears, often aggregated as a mean score per word in a text. Several corpora are used to derive these indices, and transformations such as log-scaling or lemma-based calculations are applied for normalization or variant types.

### Corpus Used
- British National Corpus (BNC)  
- Brown Corpus (KF)  
- Corpus of Contemporary American English (COCA)  
- SUBTLEXus  
- TOEFL11 Corpus

### Register
Varies by corpus, including written/spoken registers, academic/non-academic texts, and proficiency levels.

### Calculated Indices

---

#### BNC Word Range

- **Methodology**: Mean range score across two registers (written & spoken)
- **Indices**:
  - BNC_Written_Range_AW  
  - BNC_Written_Range_CW  
  - BNC_Written_Range_FW  
  - BNC_Spoken_Range_AW  
  - BNC_Spoken_Range_CW  
  - BNC_Spoken_Range_FW  
- **References**: BNC Consortium, 2007

---

#### Brown Corpus Word Range
- **Methodology**: Register Range (Ncats) and Document Range (Nsamp).
- **Indices**:
  - KF_Ncats_AW  
  - KF_Ncats_CW  
  - KF_Ncats_FW  
  - KF_Nsamp_AW  
  - KF_Nsamp_CW  
  - KF_Nsamp_FW  
- **References**: Kucera & Francis, 1967

---

#### COCA Word Range
- **Methodology**: Measures raw, lemma-based, and log-transformed range values across five COCA registers (academic, fiction, magazine, news, spoken)
- **Indices**: Includes Raw Word Range, Logarithmic Word Range, Lemma-Based Word Range (Raw & Log), and Types Word Range (Raw & Logarithmic) (e.g., COCA_Academic_Range_AW)
- **References**: Davies, 2009

---

#### SUBTLEXus Word Range

- **Methodology**: Raw and log-transformed mean range scores from subtitle-based spoken discourse
- **Indices**:
  - SUBTLEXus_Range_AW  
  - SUBTLEXus_Range_CW  
  - SUBTLEXus_Range_FW  
  - SUBTLEXus_Range_AW_Log  
  - SUBTLEXus_Range_CW_Log  
  - SUBTLEXus_Range_FW_Log  
- **References**: Brysbaert & New, 2009

---

#### TOEFL11 Word Range

- **Methodology**: Measures word and lemma distribution across proficiency levels using raw, log-transformed, and type-based scores
- **Indices**: Includes Raw Word Range, Log Word Range, Lemma Range (Raw & Log), and Lemma Range Types (Raw & Log) (e.g., NNS_Raw_Range_High_AW)
- **References**: Blanchard et al., 2013; Monteiro et al., 2020