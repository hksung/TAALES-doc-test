# Age of Acquisition (AoA) and Age of Exposure (AoE)

**Age of acquisition (AoA)** and **age of exposure (AoE)** are indices of lexical sophistication that refer to the average age when someone learns a word (AoA) or first encounters it (AoE) as a native speaker. Studies (Kuperman et al., 2012; Dascalu et al., 2016) show that these indices can help explain how difficult it is for language learners to process words, i.e., words learned later in life, i.e., which have higher AoA/AoE scores, are often less familiar, and reflect more advanced vocabulary use.

*TAALES 1.0* calculates AoA for: *(a)* all words, *(b)* content words (e.g., nouns, verbs), and *(c)* function words (e.g., prepositions, conjunctions). The mean AoA score of a text is calculated by dividing the sum of all / content / function words in a text to the number of all / content / function words that have AoA scores.

*TAALES 2.0*  calculates AoE as an incremental score for words across 13 grade levels using LDA modeling. The AoE is measured in four different ways: 
- *(a)* inverse average similarity; 
- *(b)* inverse linear regression slope; 
- *(c)* index polynomial fit of degree 3 with an LDA cosine threshold of 0.40; 
- *(d)* index polynomial fit of degree 3 with inflection point. 
All these indices provide a measure of similarity based on words co-occurring in similar contexts.

