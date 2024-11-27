---
sort: 5
---

## Age of Acquisition

- **Definition:** Age of acquisition (AoA) and/or Age of exposure (AoE) indicate the average age a native speaker learns or first encounters a word. Studies (e.g., Kuperman et al., 2012; Dascalu et al., 2016) show that higher AoA/AoE scores correlate with less familiar, more advanced vocabulary, reflecting greater difficulty for language learners.

- Tool: 
	- *TAALES 1.0* calculates AoA for: *(a)* all words, *(b)* content words (e.g., nouns, verbs), and *(c)* function words (e.g., prepositions, conjunctions). The mean AoA score of a text is calculated by dividing the sum of all / content / function words in a text to the number of all / content / function words that have AoA scores.

	- *TAALES 2.0*  calculates AoE as an incremental score for words across 13 grade levels using Latent Dirichlet Allocation (LDA) modeling. The AoE is measured in four different ways: 
		- *(a)* inverse average similarity; 
		- *(b)* inverse linear regression slope; 
		- *(c)* index polynomial fit of degree 3 with an LDA cosine threshold of 0.40; 
		- *(d)* index polynomial fit of degree 3 with inflection point. 
		- All these indices provide a measure of similarity based on words co-occurring in similar contexts.

