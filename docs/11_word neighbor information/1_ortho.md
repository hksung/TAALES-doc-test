# Ortographic neighborhood
**Ortographic neighborhood** refers to the set of words that can be formed by changing a single letter in a given word, resulting in a new valid word. The closest ortographic neighbors are those words that require the fewest character edits to transform into the target word.

### Ortho_N
- **Description**: Number of ortographic neighbors for a particular word.
- **Methodology**: Count
- **Word types**:
    - ***Ortho_N***: All words (AW)
    - ***Ortho_N_CW***: Content words (CW)
    - ***Ortho_N_FW***: Function words (FW)
- **Corpus**: Not applicable (NA)
- **Register**: Not applicable (NA)
- **References**: Balota et al., 2007

### Freq_N
- **Description**: Average frequency of ortographic neighborhood for a particular word.
- **Methodology**: Mean frequency in HAL corpus
- **Word types**:
    - ***Freq_N***: All words (AW)
    - ***Freq_N_CW***: Content words (CW)
    - ***Freq_N_FW***: Function words (FW)
- **Corpus**: HAL (Hyperspace Analogue to Language)
- **Register**: Not applicable (NA)
- **References**: Balota et al., 2007; Lund & Burgess, 1996

### OLD
- **Description**: Average Levenshtein Distance of 20 closest orthographic neighbors for a particular word.
- **Methodology**: Mean Levenshtein distances
- **Word types**:
    - ***OLD***: All words (AW)
    - ***OLD_CW***: Content words (CW)
    - ***OLD_FW***: Function words (FW)
- **Corpus**: Not applicable (NA)
- **Register**: Not applicable (NA)
- **References**: Yarkoni et al., 2008; Balota et al., 2007


### OLDF
- **Description**: Average log HAL frequency of 20 closest orthographic neighbors for a particular word.
- **Methodology**: Mean logarithmic frequencies in HAL corpus
- **Word types**:
    - ***OLDF***: All words (AW)
    - ***OLDF_CW***: Content words (CW)
    - ***OLDF_FW***: Function words (FW)
- **Corpus**: HAL (Hyperspace Analogue to Language) ???
- **Register**: Not applicable (NA)
- **References**: Yarkoni et al., 2008; Balota et al., 2007; Lund & Burgess, 1996