# Phonological neighborhood
**Phonological neighborhood** refers to a set of words that are phonetically similar to a target word, typically differing by only one phoneme through addition, deletion, or substitution.

### Phono_N
- **Description**: Number of phonological neighbors for a particular word.
- **Methodology**: Count
- **Types**:
    - **Excluding homophones**: ???
        - ***Phono_N***: All words (AW)
        - ***Phono_N_CW***: Content words (CW)
        - ***Phono_N_FW***: Function words (FW)
    - **Including homophones**:
        - ***Phono_N_H***: All words (AW)
        - ***Phono_N_H_CW***: Content words (CW)
        - ***Phono_N_H_FW***: Function words (FW)
- **Corpus**: Not applicable (NA)
- **Register**: Not applicable (NA)
- **References**: Balota et al., 2007

### Freq_N_P
- **Description**: Average frequency of phonological neighborhood for a particular word.
- **Methodology**: Mean frequency in HAL corpus
- **Types**:
    - **Excluding homophones**: 
        - ***Freq_N_P***: All words (AW)
        - ***Freq_N_P_CW***: Content words (CW)
        - ***Freq_N_P_FW***: Function words (FW)
    - **Including homophones**:
        - ***Freq_N_PH***: All words (AW)
        - ***Freq_N_PH_CW***: Content words (CW)
        - ***Freq_N_PH_FW***: Function words (FW)
- **Corpus**: HAL (Hyperspace Analogue to Language)
- **Register**: Not applicable (NA)
- **References**: Balota et al., 2007; Lund & Burgess, 1996

### PLD
- **Description**: Average Levenshtein Distance of 20 closest phonological neighbors for a particular word.
- **Methodology**: Mean Levenshtein distances
- **Word types**:
    - ***PLD***: All words (AW)
    - ***PLD_CW***: Content words (CW)
    - ***PLD_FW***: Function words (FW)
- **Corpus**: Not applicable (NA)
- **Register**: Not applicable (NA)
- **References**: Yarkoni, Balota, & Yap, 2008; Balota et al., 2007

### PLDF
- **Description**: Average log HAL frequency of 20 closest phonographic neighbors for a particular word.
- **Methodology**: Mean logarithmic frequencies in HAL corpus
- **Word types**:
    - ***PLDF***: All words (AW)
    - ***PLDF_CW***: Content words (CW)
    - ***PLDF_FW***: Function words (FW)
- **Corpus**: HAL (Hyperspace Analogue to Language)
- **Register**: Not applicable (NA)
- **References**: Balota et al., 2007; Lund & Burgess, 1996