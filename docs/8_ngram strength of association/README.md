---
sort: 8
---

## ngram strength of association
- **Definition**: Ngram strength of association (SOA) measures how strongly the words in an ngram are related to each other based on their co-occurrence patterns. These indicies are valuable for understanding collocations, idiomatic expressions, and overall cohesion within a text (Gablasova et al., 2017; O'Donnell et al., 2013).

*TAALES 2.0* captures the dependency between words within bigrams and trigrams, using the following statistical measures, which are calculated based on the COCA subcorpora:
- *(a) MI* (Mutual information) highlights lower frequency combinations that are highly exclusive. This measure is highly susceptible to low frequencies. A high MI score suggests a rare, yet strong association between the words.
- *(b) MI^2^* (Mutual information squared) fixes the low-frequency bias of the MI score and awards strong associations not only on low frequency by squaring the numerator. 
- *(c) T* (T score) emphasizes the most frequent combinations of words. A high T score indicates frequent, but weak association between the words (e.g., generic phrases).
- *(d) DP* (Delta P) studies directional associations and is useful for predictive text models. A high Delta P score indicates predictive strength, where one word reliably precedes another.
- *(e) AC* (Approximate Collexeme) is a measure of how strongly two items co-occur. A high AC score indicates frequently co-occuring, semantically coehsive phrases, while a low score indicates generic or loosely associated phrases.

Studies (Granger & Bestgen, 2014) show that intermediate L2 learners tend to underuse collocations with high MI and MI^2^ scores, and to overuse collocations with high T-Scores.