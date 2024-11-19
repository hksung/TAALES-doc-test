# Ngram frequency

**Ngram frequency** provides insights into the lexical sophistication of a text based on the number of occurences of *n* number of words. Research (O'Donnell et al., 2013; Bestgen & Granger, 2014) shows that, while high-frequency ngrams can offer information about the use of conventionalized language and formulaic sequences in texts, it does not necessarily have any implications for proficiency on its own. Instead, more information about ngram use, such as range and association, is needed.

*TAALES 2.0* calculates the sum and logarithmic frequency scores for bigrams (two units) and trigrams (three units) and compares them to their proportions in multiple subcorpora of two reference corpora (*BNC* and *COCA*).


# Ngram range

**Ngram range** represents the distribution or variety of n-grams across different sections or registers of a corpus, providing insights into their spread or generalizability. It is particularly useful in determining how widely used specific sequences of words are in diverse contexts within a corpus.

*TAALES 2.0* gives the mean bigram and trimgram range scores, calculated by dividing the sum of range scores by the number of bigrams / trigrams in text with range scores, looking at five subcorpora of COCA (academic, fiction, magazine, news, spoken).

# Ngram association

**Ngram association** measures how strongly the words in an ngram are related to each other based on their co-occurrence patterns. These indicies are valuable for understanding collocations, idiomatic expressions, and overall cohesion within a text (Gablasova et al., 2017; O'Donnell et al., 2013).

*TAALES 2.0* captures the dependency between words within bigrams and trigrams, using the following statistical measures, which are calculated based on the COCA subcorpora:
- *(a) MI* (Mutual information) highlights lower frequency combinations that are highly exclusive. This measure is highly susceptible to low frequencies. A high MI score suggests a rare, yet strong association between the words.
- *(b) MI^2^* (Mutual information squared) fixes the low-frequency bias of the MI score and awards strong associations not only on low frequency by squaring the numerator. 
- *(c) T* (T score) emphasizes the most frequent combinations of words. A high T score indicates frequent, but weak association between the words (e.g., generic phrases).
- *(d) DP* (Delta P) studies directional associations and is useful for predictive text models. A high Delta P score indicates predictive strength, where one word reliably precedes another.
- *(e) AC* (Approximate Collexeme) is a measure of how strongly two items co-occur. A high AC score indicates frequently co-occuring, semantically coehsive phrases, while a low score indicates generic or loosely associated phrases.

Studies (Granger & Bestgen, 2014) show that intermediate L2 learners tend to underuse collocations with high MI and MI^2^ scores, and to overuse collocations with high T-Scores.
