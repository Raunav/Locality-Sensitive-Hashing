# Locality-Sensitive-Hashing
This project focuses on employing Locality-Sensitive Hashing (LSH) techniques to discover similar documents in a dataset of over 1,500 paragraphs. The objective was to identify nearly identical paragraphs based on their content, leveraging concepts like shingling, minhashing, and the banding technique.

## Project Overview

The project involves implementing a naive Python solution to apply the LSH algorithm for document similarity detection. The dataset contains AI-generated text with potential overlaps and hidden similarities, challenging us to uncover them using algorithmic methods.

### Tasks
1. **Shingle Representation**:
   - Implemented shingling to represent paragraphs as sets of overlapping subsequences (e.g., k-grams).
   - Explored the effect of different shingle sizes on similarity detection.

2. **Minhashing**:
   - Applied minhashing to summarize the sets into compact, similarity-preserving signatures.

3. **Banding Technique**:
   - Utilized the banding technique to reduce dimensionality and group similar documents into candidate pairs.

4. **Similarity Comparison**:
   - Computed pairwise similarities among candidate pairs and identified the top five most similar document pairs.

---

## Key Outcomes
- Successfully implemented the LSH technique to uncover hidden similarities in the dataset.
- Validated the necessity of the banding technique in reducing computational complexity and increasing efficiency.
- Discovered pairs of documents with the highest degree of similarity, demonstrating the algorithm's effectiveness.

---

## Results and Observations
1. **Shingle Size**:
   - Chose 3-grams as the shingle size for its balance between precision and generalization.

2. **Efficiency**:
   - Direct pairwise comparison of signature matrices proved computationally expensive; LSH efficiently grouped similar candidates for targeted comparison.

3. **Top Similar Documents**:
   - Identified five pairs of nearly identical documents with high similarity scores.

---

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib

