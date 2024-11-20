# Age of Acquisition (AoA) and Age of Exposure (AoE)

**Age of acquisition (AoA)** and **age of exposure (AoE)** are indices of lexical sophistication that refer to the average age when someone learns a word (AoA) or first encounters it (AoE) as a native speaker. Studies (Kuperman et al., 2012; Dascalu et al., 2016) show that these indices can help explain how difficult it is for language learners to process words, i.e., words learned later in life, i.e., which have higher AoA/AoE scores, are often less familiar, and reflect more advanced vocabulary use.

*TAALES 1.0* calculates AoA for: *(a)* all words, *(b)* content words (e.g., nouns, verbs), and *(c)* function words (e.g., prepositions, conjunctions). The mean AoA score of a text is calculated by dividing the sum of all / content / function words in a text to the number of all / content / function words that have AoA scores.

*TAALES 2.0*  calculates AoE as an incremental score for words across 13 grade levels using LDA modeling. The AoE is measured in four different ways: 
- *(a)* inverse average similarity; 
- *(b)* inverse linear regression slope; 
- *(c)* index polynomial fit of degree 3 with an LDA cosine threshold of 0.40; 
- *(d)* index polynomial fit of degree 3 with inflection point. 
All these indices provide a measure of similarity based on words co-occurring in similar contexts.


# Contextual distinctiveness

**Contextual distinctiveness** refers to how many different psychological, lexical or semantic contexts a word typically appears in, which can impact the perceived difficulty of a word. Research (Berger et al., 2017) shows that more proficient language learners tend to use words with higher contextual distinctiveness and difficulty.

*TAALES 2.0* measures contextual distinctiveness for *(a)* all words, *(b)* content words (e.g., nouns, verbs), and *(c)* function words (e.g., prepositions, conjunctions) using several indices: 
- *(1) McD* (McDonald & Shillcock, 2001), a corpus-based measure which calculates how predictable a word is based on its 5-word context; 
- *(2) USF norms* (Nelson et al., 2004), which track how often a word is suggested by different cues in word association tests. 

These indices capture how broadly or narrowly a word is used in various contexts by looking at:
- *(1)* the variety of words that come to mind in response to a given word in free association; 
- *(2)* the number of different prompts that trigger a specific word in free association tasks; 
- *(3)* the probability of the word appearing near highly frequent words within a five-word window in text;
- *(4)* the variability of contexts in which the word appears across 1,000-word sections of text. 


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

# Word neighbor information

**Word neighborhood information** refers to the way words are connected based on shared orthographic (spelling), phonographic (spelling and sound), and phonological (sound) features (Peereman & Content, 1997). Words with many neighbors, i.e., those that can be formed by changing a letter or sound, are usually processed faster, while words with few neighbors tend to be formally complex and processed more slowly. Complex words with few neighbors, often seen in high-quality writing, can influence readability and perceived lexical sophistication.

In *TAALES 2.0*, key indices for measuring word neighborhood include counts of orthographic, phonological, and phonographic neighbors, as well as their frequency (how common these neighbors are) and Levenshtein distance (average letter or phoneme changes needed to reach the nearest neighbors).


# Word recognition norms

**Word recognition norms** measure the cognitive effort required to recognize and process words. These norms are based on average response times (latencies) and accuracy scores from lexical decision tasks (identifying if a word is real or not) and word-naming tasks (time taken to begin pronouncing a word) by native English speakers (Berger et al., 2017).

Such norms provide insights into the ease or difficulty of processing specific words. They are valuable for modeling vocabulary development and assessing lexical proficiency, as words with longer response times generally indicate greater cognitive processing demands, potentially requiring higher language proficiency for quick access.

In *TAALES 2.0*, these norms are calculated in various ways, such as mean response times, z-scores (standardized latencies), standard deviations, and accuracy rates, reflecting performance on lexical decision and word-naming tasks.


# References
Berger, C., Crossley, S. & Kyle, K. (2017). Using Native-Speaker Psycholinguistic Norms to Predict Lexical Proficiency and Development in Second-Language Production. *Applied Linguistics*, 40(1), 22–42. https://doi.org/10.1093/applin/amx005
Bestgen, Y., & Granger, S. (2014). Quantifying the development of phraseological competence in L2 English writing: An automated approach. *Journal of Second Language Writing*, 26, 28-41. https://doi.org/10.1016/j.jslw.2014.09.004
Dascalu, M., McNamara, D., Crossley, S., & Trausan-Matu, S. (2016). Age of Exposure: A Model of Word Learning. *Proceedings of the AAAI Conference on Artificial Intelligence*, 30(1), 2928-2934. https://doi.org/10.1609/aaai.v30i1.10372
Gablasova, D., Brezina, V. & McEnery, T. (2017). Collocations in Corpus-Based Language Learning Research: Identifying, Comparing, and Interpreting the Evidence. *Language Learning*, 67, 155-179. https://doi.org/10.1111/lang.12225
Granger, S. & Bestgen, Y. (2014). The use of collocations by intermediate vs. advanced non-native writers: A bigram-based study. *International Review of Applied Linguistics in Language Teaching*, 52(3), 229-252. https://doi.org/10.1515/iral-2014-0011
Kuperman, V., Stadthagen-Gonzalez, H. & Brysbaert, M. (2012). Age-of-acquisition ratings for 30,000 English words. *Behav Res* 44, 978–990. https://doi.org/10.3758/s13428-012-0210-4
McDonald, S. A., & Shillcock, R. C. (2001). Rethinking the Word Frequency Effect: The Neglected Role of Distributional Information in Lexical Processing. *Language and Speech*, 44(3), 295-322. https://doi.org/10.1177/00238309010440030101
Nelson, D.L., McEvoy, C.L. & Schreiber, T.A. (2004). The University of South Florida free association, rhyme, and word fragment norms. *Behavior Research Methods, Instruments, & Computers*, 36, 402–407. https://doi.org/10.3758/BF03195588
O'Donnell, M. B., Römer, U., & Ellis, N. C. (2013). The development of formulaic sequences in first and second language writing: Investigating effects of frequency, association, and native norm. *International Journal of Corpus Linguistics*, 18(1), 83–108. https://doi.org/10.1075/ijcl.18.1.07odo
Peereman, R., & Content, A. (1997). Orthographic and phonological neighborhoods in naming: Not all neighbors are equally influential in orthographic space. *Journal of Memory and Language*, 37, 382–410. https://doi.org/10.1006/jmla.1997.2516
